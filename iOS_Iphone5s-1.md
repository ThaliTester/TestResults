#### Test 6539483973f7970_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/6539483973f7970/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/739D0CE3-A6ED-4768-9875-9F75CC6B0165/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/739D0CE3-A6ED-4768-9875-9F75CC6B0165/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/6539483973f7970/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/6539483973f7970/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/D1B7CB67-E364-4EFA-8A0C-B81EA0158F05/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51006"
,(lldb)     command script import "/tmp/739D0CE3-A6ED-4768-9875-9F75CC6B0165/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-04-06 03:09:52.633 ThaliTest[2896:5518065] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/D4357363-17A3-4BDC-8E67-E08EC57C22EF/Library/Cookies/Cookies.binarycookies
,2016-04-06 03:09:52.892 ThaliTest[2896:5518065] Apache Cordova native platform version 4.1.0 is starting.
,2016-04-06 03:09:52.893 ThaliTest[2896:5518065] Multi-tasking -> Device: YES, App: YES
,2016-04-06 03:09:52.911 ThaliTest[2896:5518065] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-04-06 03:09:53.722 ThaliTest[2896:5518065] Using UIWebView
2016-04-06 03:09:53.724 ThaliTest[2896:5518065] [CDVTimer][handleopenurl] 0.158012ms
,2016-04-06 03:09:53.728 ThaliTest[2896:5518065] [CDVTimer][intentandnavigationfilter] 3.849983ms
2016-04-06 03:09:53.729 ThaliTest[2896:5518065] [CDVTimer][gesturehandler] 0.138998ms
2016-04-06 03:09:53.729 ThaliTest[2896:5518065] [CDVTimer][TotalPluginS,tartup] 4.764020ms
,2016-04-06 03:09:56.997 ThaliTest[2896:5518065] Resetting plugins due to page load.
,2016-04-06 03:09:58.491 ThaliTest[2896:5518065] Finished load of: file:///var/mobile/Containers/Bundle/Application/D1B7CB67-E364-4EFA-8A0C-B81EA0158F05/ThaliTest.app/www/index.html
,2016-04-06 03:09:58.680 ThaliTest[2896:5518065] JXcore Cordova plugin initializing
2016-04-06 03:09:58.681 ThaliTest[2896:5518210] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-04-06 03:10:07.064 ThaliTest[2896:5518210] jxcore: didRegisterToNative peerAvailabilityChanged
2016-04-06 03:10:07.064 ThaliTest[2896:5518210] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-04-06 03:10:07.065 ThaliTest[2896:5518210] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-04-06 03:10:07.068 ThaliTest[2896:5518210] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5s-1
WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D1B7CB67-E364-4EFA-8A0C-B81EA0158F05/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D1B7CB67-E364-4EFA-8A0C-B81EA0158F05/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D1B7CB67-E364-4EFA-8A0C-B81EA0158F05/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D1B7CB67-E364-4EFA-8A0C-B81EA0158F05/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D1B7CB67-E364-4EFA-8A0C-B81EA0158F05/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D1B7CB67-E364-4EFA-8A0C-B81EA0158F05/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D1B7CB67-E364-4EFA-8A0C-B81EA0158F05/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D1B7CB67-E364-4EFA-8A0C-B81EA0158F05/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D1B7CB67-E364-4EFA-8A0C-B81EA0158F05/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D1B7CB67-E364-4EFA-8A0C-B81EA0158F05/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D1B7CB67-E364-4EFA-8A0C-B81EA0158F05/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D1B7CB67-E364-4EFA-8A0C-B81EA0158F05/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D1B7CB67-E364-4EFA-8A0C-B81EA0158F05/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D1B7CB67-E364-4EFA-8A0C-B81EA0158F05/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D1B7CB67-E364-4EFA-8A0C-B81EA0158F05/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D1B7CB67-E364-4EFA-8A0C-B81EA0158F05/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D1B7CB67-E364-4EFA-8A0C-B81EA0158F05/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D1B7CB67-E364-4EFA-8A0C-B81EA0158F05/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D1B7CB67-E364-4EFA-8A0C-B81EA0158F05/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D1B7CB67-E364-4EFA-8A0C-B81EA0158F05/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D1B7CB67-E364-4EFA-8A0C-B81EA0158F05/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D1B7CB67-E364-4EFA-8A0C-B81EA0158F05/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 59790
ok 1 Should throw
# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 59792
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
DEBUG createNativeListener: listening 59795
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
DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
# setup
DEBUG createNativeListener: incoming socket close
,# 4. native server connections all up
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 59799
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
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
,# setup
DEBUG createNativeListener: incoming socket close
,# 5. native server - closing incoming stream cleans outgoing socket
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 59804
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
DEBUG createNativeListener: listening 59808
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 14 we should not have gotten an error
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
DEBUG createNativeListener: listening 59812
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
DEBUG createNativeListener: listening 59816
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
DEBUG createNativeListener: listening 59820
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
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
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
DEBUG createNativeListener: listening 59872
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 31 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
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
DEBUG createNativeListener: listening 59876
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
,ok 58 thirdPromise - in resolve
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
,ok 69 firstPromise - in catch
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
,[{"uuid":"23004744-777a-4286-80e8-7c39ced52031","data":"custom data"},{"uuid":"b9648362-bd7c-4ccf-8c9e-e657f2368bf5","data":"custom data"},{"uuid":"1e708892-c95f-4713-9eb4-ebedb0ff7757","data":"custom data"},{"uuid":"c99173ba-aafb-407b-a44f-72a198cb56d8","data":"custom data"}]
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
DEBUG createNativeListener: listening 59886
2016-04-06 03:13:22.058 ThaliTest[2896:5518210] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-06 03:13:22.060 ThaliTest[2896:5518210] jxcore: stopListeningForAdvertisements: success
ok 91 error should be null
ok 92 error should be null
,2016-04-06 03:13:22.063 ThaliTest[2896:5518210] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-06 03:13:22.065 ThaliTest[2896:5518210] jxcore: stopListeningForAdvertisements: success
,ok 93 error should be null
,ok 94 error should be null
,# teardown
,2016-04-06 03:13:22.231 ThaliTest[2896:5518210] jxcore: stopAdvertisingAndListening
2016-04-06 03:13:22.232 ThaliTest[2896:5518210] THEMultipeerManager stopping peer
2016-04-06 03:13:22.232 ThaliTest[2896:5518210] jxcore: stopAdvertisingAndListening: success
2016-04-06 03:13:22.232 ThaliTest[2896:5518210] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-06 03:13:22.233 ThaliTest[2896:5518210] jxcore: stopListeningForAdvertisements: success
,ok 95 error should be null
,ok 96 error should be null
,# setup
,# 26. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 59888
,2016-04-06 03:13:22.431 ThaliTest[2896:5518210] jxcore: startListeningForAdvertisements
,2016-04-06 03:13:22.432 ThaliTest[2896:5518210] multipeer manager: start client restart timer: 0x17d8d270
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-06 03:13:22.433 ThaliTest[2896:5518210] jxcore: startListeningForAdvertisements: success
,ok 97 error should be null
,ok 98 error should be null
,2016-04-06 03:13:22.568 ThaliTest[2896:5518210] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-06 03:13:22.569 ThaliTest[2896:5518210] jxcore: startListeningForAdvertisements: success
,ok 99 error should be null
,ok 100 error should be null
,# teardown
,2016-04-06 03:13:22.796 ThaliTest[2896:5518210] jxcore: stopAdvertisingAndListening
2016-04-06 03:13:22.796 ThaliTest[2896:5518210] THEMultipeerManager stopping peer
2016-04-06 03:13:22.796 ThaliTest[2896:5518210] jxcore: stopAdvertisingAndListening: success
2016-04-06 03:13:22.796 ThaliTest[2896:5518210] jxcore: stopListeningForAdvertisements
2016-04-06 03:13:22.796 ThaliTest[2896:5518210] multipeer manager: stop client timer
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-06 03:13:22.797 ThaliTest[2896:5518210] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 101 error should be null
,ok 102 error should be null
,# setup
,# 27. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 59890
,2016-04-06 03:13:22.983 ThaliTest[2896:5518210] jxcore: startUpdateAdvertisingAndListening
,2016-04-06 03:13:22.984 ThaliTest[2896:5518210] server: starting 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:1
2016-04-06 03:13:22.984 ThaliTest[2896:5518210] multipeer manager: start client restart timer: 0x17d8d270
,2016-04-06 03:13:22.985 ThaliTest[2896:5518210] THEMultipeerManager initialized peer 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:1
2016-04-06 03:13:22.985 ThaliTest[2896:5518210] jxcore: startUpdateAdvertisingAndListening: success
,ok 103 error should be null
ok 104 error should be null
,2016-04-06 03:13:23.043 ThaliTest[2896:5518210] jxcore: startUpdateAdvertisingAndListening
2016-04-06 03:13:23.043 ThaliTest[2896:5518210] THEMultipeerManager stopping peer
2016-04-06 03:13:23.044 ThaliTest[2896:5518210] multipeer manager: stop client ti,mer
2016-04-06 03:13:23.044 ThaliTest[2896:5518210] server: starting 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:2
2016-04-06 03:13:23.044 ThaliTest[2896:5518210] multipeer manager: start client restart timer: 0x17d8d270
2016-04-06 03:13:23.044 ThaliTest[2896:5518210] THEMultipeerManager initialized peer 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:2
2016-04-06 03:13:23.044 ThaliTest[2896:5518210] jxcore: startUpdateAdvertisingAndListening: success
,ok 105 error should be null
ok 106 error should be null
,# teardown
,2016-04-06 03:13:23.391 ThaliTest[2896:5518210] jxcore: stopAdvertisingAndListening
2016-04-06 03:13:23.392 ThaliTest[2896:5518210] THEMultipeerManager stopping peer
2016-04-06 03:13:23.392 ThaliTest[2896:5518210] multipeer manager: stop client timer
20,16-04-06 03:13:23.392 ThaliTest[2896:5518210] jxcore: stopAdvertisingAndListening: success
2016-04-06 03:13:23.392 ThaliTest[2896:5518210] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-06 03:13:23.393 ThaliTest[2896:5518210] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 107 error should be null
ok 108 error should be null
# setup
,# 28. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 59895
2016-04-06 03:13:46.431 ThaliTest[2896:5518210] jxcore: stopAdvertisingAndListening
2016-04-06 03:13:46.431 ThaliTest[2896:5518210] THEMultipeerManager stopping peer
2016-04-06 03:13:46.431 ThaliTest[2896:5518210] jxcore: stopAdvertisingAndListening: success
ok 109 error should be null
,ok 110 error should be null
2016-04-06 03:13:46.434 ThaliTest[2896:5518210] jxcore: stopAdvertisingAndListening
2016-04-06 03:13:46.435 ThaliTest[2896:5518210] THEMultipeerManager stopping peer
2016-04-06 03:13:46.435 ThaliTest[2896:5518210] jxcore: stopAdvertisingAndListening: success
,ok 111 error should be null
ok 112 error should be null
# teardown
,2016-04-06 03:13:50.013 ThaliTest[2896:5518210] jxcore: stopAdvertisingAndListening
2016-04-06 03:13:50.013 ThaliTest[2896:5518210] THEMultipeerManager stopping peer
2016-04-06 03:13:50.013 ThaliTest[2896:5518210] jxcore: stopAdvertisingAndListening: success
2016-04-06 03:13:50.014 ThaliTest[2896:5518210] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-06 03:13:50.014 ThaliTest[2896:5518210] jxcore: stopListeningForAdvertisements: success
ok 113 error should be null
ok 114 error should be null
# setup
,# 29. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 59897
ok 115 first call should succeed
ok 116 first call should succeed
ok 117 specific error should be returned
# teardown
,2016-04-06 03:13:59.012 ThaliTest[2896:5518210] jxcore: stopAdvertisingAndListening
2016-04-06 03:13:59.013 ThaliTest[2896:5518210] THEMultipeerManager stopping peer
2016-04-06 03:13:59.013 ThaliTest[2896:5518210] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-06 03:13:59.013 ThaliTest[2896:5518210] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-06 03:13:59.014 ThaliTest[2896:5518210] jxcore: stopListeningForAdvertisements: success
ok 118 error should be null
ok 119 error should be null
# setup
,# 30. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 59899
2016-04-06 03:13:59.169 ThaliTest[2896:5518210] jxcore: startListeningForAdvertisements
2016-04-06 03:13:59.169 ThaliTest[2896:5518210] multipeer manager: sta,rt client restart timer: 0x17d8d270
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-06 03:13:59.170 ThaliTest[2896:5518210] jxcore: startListeningForAdvertisements: success
,2016-04-06 03:13:59.210 ThaliTest[2896:5518210] jxcore: startUpdateAdvertisingAndListening
2016-04-06 03:13:59.210 ThaliTest[2896:5518210] server: starting 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:3
2016-04-06 03:13:59.211 ThaliTest[2896:5518210] THEMultipeerManager initialized peer 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:3
2016-04-06 03:13:59.211 ThaliTest[2896:5518210] jxcore: startUpdateAdvertisingAndListening: success
ok 120 called only once
ok 121 discovery state matches
ok 122 advertising state matches
# teardown
,2016-04-06 03:13:59.445 ThaliTest[2896:5518210] jxcore: stopAdvertisingAndListening
2016-04-06 03:13:59.445 ThaliTest[2896:5518210] THEMultipeerManager stopping peer
2016-04-06 03:13:59.446 ThaliTest[2896:5518210] jxcore: stopAdvertisingAndListening: success
2016-04-06 03:13:59.446 ThaliTest[2896:5518210] jxcore: stopListeningForAdvertisements
2016-04-06 03:13:59.446 ThaliTest[2896:5518210] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-06 03:13:59.447 ThaliTest[2896:5518210] jxcore: stopListeningForAdvertisements: success
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
,ok 131 error should be null
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
,ok 137 error should be null
,# setup
,# 34. Can call start/stopListeningForAdvertisements
,2016-04-06 03:14:46.122 ThaliTest[2896:5518210] jxcore: startListeningForAdvertisements
2016-04-06 03:14:46.122 ThaliTest[2896:5518210] multipeer manager: start client restart timer: 0x17d8d270
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-06 03:14:46.123 ThaliTest[2896:5518210] jxcore: startListeningForAdvertisements: success
ok 138 Can call startListeningForAdvertisements without error
2016-04-06 03:14:46.124 ThaliTes,t[2896:5518210] jxcore: stopListeningForAdvertisements
2016-04-06 03:14:46.124 ThaliTest[2896:5518210] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-06 03:14:46.125 ThaliTest[2896:5518210] jxcore: stopListeningForAdvertisements: success
ok 139 Can call stopListeningForAdvertisements without error
# teardown
,2016-04-06 03:14:46.181 ThaliTest[2896:5518210] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-06 03:14:46.182 ThaliTest[2896:55182,10] jxcore: stopListeningForAdvertisements: success
ok 140 Should be able to call stopListeningForAdvertisements in teardown
2016-04-06 03:14:46.183 ThaliTest[2896:5518210] jxcore: stopAdvertisingAndListening
2016-04-06 03:14:46.183 ThaliTest[2896:55182,10] THEMultipeerManager stopping peer
2016-04-06 03:14:46.183 ThaliTest[2896:5518210] jxcore: stopAdvertisingAndListening: success
ok 141 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 35. Calling startListeningForAdvertisements twice is NOT an error
,2016-04-06 03:14:46.511 ThaliTest[2896:5518210] jxcore: startListeningForAdvertisements
2016-04-06 03:14:46.511 ThaliTest[2896:5518210] multipeer manager: start client restart timer: 0x17d8d270
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-06 03:14:46.512 ThaliTest[2896:5518210] jxcore: startListeningForAdvertisements: success
ok 142 Can call startListeningForAdvertisements without error
2016-04-06 03:14:46.513 ThaliTes,t[2896:5518210] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-06 03:14:46.513 ThaliTest[2896:5518210] jxcore: startListeningForAdvertisements: success
ok 143 Can call startListeningForAdvertisements twice without error
# teardown
,2016-04-06 03:14:46.861 ThaliTest[2896:5518210] jxcore: stopListeningForAdvertisements
2016-04-06 03:14:46.861 ThaliTest[2896:5518210] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisi,ngActive":false,"discoveryActive":false}
2016-04-06 03:14:46.862 ThaliTest[2896:5518210] jxcore: stopListeningForAdvertisements: success
ok 144 Should be able to call stopListeningForAdvertisements in teardown
2016-04-06 03:14:46.862 ThaliTest[2896:5518,210] jxcore: stopAdvertisingAndListening
2016-04-06 03:14:46.863 ThaliTest[2896:5518210] THEMultipeerManager stopping peer
2016-04-06 03:14:46.863 ThaliTest[2896:5518210] jxcore: stopAdvertisingAndListening: success
ok 145 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 36. Calling stopListeningForAdvertisements without calling start is NOT an error
,2016-04-06 03:14:47.054 ThaliTest[2896:5518210] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-06 03:14:47.055 ThaliTest[2896:5518210] jxcore: stopListeningForAdvertisements: success
ok 146 Can call stopListeningForAdvertisements without error
2016-04-06 03:14:47.056 ThaliTest[2896:5518210] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingS,tateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-06 03:14:47.056 ThaliTest[2896:5518210] jxcore: stopListeningForAdvertisements: success
ok 147 Can call stopListeningForAdvertisements without error
# teardown
,2016-04-06 03:14:47.440 ThaliTest[2896:5518210] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-06 03:14:47.440 ThaliTest[2896:5518210] jxcore: stopListeningForAdvertisements: success
ok 148 Should be able to call stopListeningForAdvertisements in teardown
2016-04-06 03:14:47.441 ThaliTest[2896:5518210] jxcore: stopAdvertisingAndListening
2016-04-06 03:14:47.441 ThaliTest[2896:55182,10] THEMultipeerManager stopping peer
2016-04-06 03:14:47.441 ThaliTest[2896:5518210] jxcore: stopAdvertisingAndListening: success
ok 149 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 37. Can call start/stopUpdateAdvertisingAndListening
,2016-04-06 03:15:33.437 ThaliTest[2896:5518210] jxcore: startUpdateAdvertisingAndListening
2016-04-06 03:15:33.437 ThaliTest[2896:5518210] server: starting 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:4
2016-04-06 03:15:33.438 ThaliTest[2896:5518210] multipeer m,anager: start client restart timer: 0x17d8d270
2016-04-06 03:15:33.438 ThaliTest[2896:5518210] THEMultipeerManager initialized peer 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:4
2016-04-06 03:15:33.438 ThaliTest[2896:5518210] jxcore: startUpdateAdvertisingAndListening: success
ok 150 Can call startUpdateAdvertisingAndListening without error
2016-04-06 03:15:33.439 ThaliTest[2896:5518210] jxcore: stopAdvertisingAndListening
2016-04-06 03:15:33.439 ThaliTest[2896:5518210] THEMultipeerManager stopping peer
,2016-04-06 03:15:33.439 ThaliTest[2896:5518210] multipeer manager: stop client timer
2016-04-06 03:15:33.444 ThaliTest[2896:5518210] jxcore: stopAdvertisingAndListening: success
ok 151 Can call stopAdvertisingAndListening without error
# teardown
,2016-04-06 03:15:33.847 ThaliTest[2896:5518210] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-06 03:15:33.848 ThaliTest[2896:55182,10] jxcore: stopListeningForAdvertisements: success
ok 152 Should be able to call stopListeningForAdvertisements in teardown
2016-04-06 03:15:33.848 ThaliTest[2896:5518210] jxcore: stopAdvertisingAndListening
2016-04-06 03:15:33.849 ThaliTest[2896:55182,10] THEMultipeerManager stopping peer
2016-04-06 03:15:33.849 ThaliTest[2896:5518210] jxcore: stopAdvertisingAndListening: success
ok 153 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 38. Calling startUpdateAdvertisingAndListening twice is NOT an error
,2016-04-06 03:15:39.672 ThaliTest[2896:5518210] jxcore: startUpdateAdvertisingAndListening
2016-04-06 03:15:39.673 ThaliTest[2896:5518210] server: starting 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:5
2016-04-06 03:15:39.673 ThaliTest[2896:5518210] multipeer manager: start client restart timer: 0x17d8d270
2016-04-06 03:15:39.673 ThaliTest[2896:5518210] THEMultipeerManager initialized peer 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:5
,2016-04-06 03:15:39.675 ThaliTest[2896:5518210] jxcore: startUpdateAdvertisingAndListening: success
ok 154 Can call startUpdateAdvertisingAndListening without error
2016-04-06 03:15:39.676 ThaliTest[2896:5518210] jxcore: startUpdateAdvertisingAndListening
2016-04-06 03:15:39.676 ThaliTest[2896:5518210] THEMultipeerManager stopping peer
2016-04-06 03:15:39.677 ThaliTest[2896:5518210] multipeer manager: stop client timer
2016-04-06 03:15:39.677 ThaliTest[2896:5518210] server: starting 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:6
2016-04-06 03:15:39.677 ThaliTest[2896:5518210] multipeer manager: start client restart timer: 0x17d8d270
2016-04-06 03:15:39.677 ThaliTest[2896:5518210] THEMultipeerManager initialized peer 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:6
,2016-04-06 03:15:39.677 ThaliTest[2896:5518210] jxcore: startUpdateAdvertisingAndListening: success
ok 155 Can call startUpdateAdvertisingAndListening twice without error
# teardown
,2016-04-06 03:15:40.503 ThaliTest[2896:5518065] client: found new peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:6
,2016-04-06 03:15:40.801 ThaliTest[2896:5518065] client: found new peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:6
,2016-04-06 03:15:41.636 ThaliTest[2896:5518065] client: found new peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:6
,2016-04-06 03:15:41.909 ThaliTest[2896:5518210] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-04-06 03:15:41.910 ThaliTest[2896:5518210] jxcore: stopListeningForAdvertisements: success
ok 156 Should be able to call stopListeningForAdvertisements in teardown
2016-04-06 03:15:41.911 ThaliTest[2896:5518210] jxcore: stopAdvertisingAndListening
2016-04-06 03:15:41.911 ThaliTest[2896:551821,0] THEMultipeerManager stopping peer
2016-04-06 03:15:41.911 ThaliTest[2896:5518210] multipeer manager: stop client timer
2016-04-06 03:15:41.911 ThaliTest[2896:5518210] jxcore: stopAdvertisingAndListening: success
ok 157 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 39. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,2016-04-06 03:16:38.007 ThaliTest[2896:5518210] jxcore: stopAdvertisingAndListening
2016-04-06 03:16:38.007 ThaliTest[2896:5518210] THEMultipeerManager stopping peer
2016-04-06 03:16:38.007 ThaliTest[2896:5518210] jxcore: stopAdvertisingAndListening: suc,cess
ok 158 Can call startUpdateAdvertisingAndListening without error
2016-04-06 03:16:38.008 ThaliTest[2896:5518210] jxcore: stopAdvertisingAndListening
2016-04-06 03:16:38.008 ThaliTest[2896:5518210] THEMultipeerManager stopping peer
2016-04-06 03:16:38.008 ThaliTest[2896:5518210] jxcore: stopAdvertisingAndListening: success
ok 159 Can call stopAdvertisingAndListening without error
# teardown
,2016-04-06 03:16:38.112 ThaliTest[2896:5518210] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-06 03:16:38.113 ThaliTest[2896:55182,10] jxcore: stopListeningForAdvertisements: success
ok 160 Should be able to call stopListeningForAdvertisements in teardown
2016-04-06 03:16:38.113 ThaliTest[2896:5518210] jxcore: stopAdvertisingAndListening
2016-04-06 03:16:38.114 ThaliTest[2896:5518210] THEMultipeerManager stopping peer
2016-04-06 03:16:38.114 ThaliTest[2896:5518210] jxcore: stopAdvertisingAndListening: success
ok 161 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 40. cannot call connect when start listening for advertisements is not active
,2016-04-06 03:16:38.332 ThaliTest[2896:5518210] jxcore: connect foo
2016-04-06 03:16:38.333 ThaliTest[2896:5518210] jxcore: connect: fail: Start browsing first
not ok 162 got right error
  ---
    operator: equal
    expected: 'startListeningForAdvertisements is not active'
    actual:   'Start browsing first'
  ...
# teardown
,2016-04-06 03:16:38.473 ThaliTest[2896:5518210] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-06 03:16:38.473 ThaliTest[2896:55182,10] jxcore: stopListeningForAdvertisements: success
ok 163 Should be able to call stopListeningForAdvertisements in teardown
2016-04-06 03:16:38.474 ThaliTest[2896:5518210] jxcore: stopAdvertisingAndListening
2016-04-06 03:16:38.474 ThaliTest[2896:5518210] THEMultipeerManager stopping peer
2016-04-06 03:16:38.474 ThaliTest[2896:5518210] jxcore: stopAdvertisingAndListening: success
ok 164 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 41. peerAvailabilityChange is called
,2016-04-06 03:16:38.642 ThaliTest[2896:5518210] jxcore: startUpdateAdvertisingAndListening
2016-04-06 03:16:38.642 ThaliTest[2896:5518210] server: starting 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:7
2016-04-06 03:16:38.643 ThaliTest[2896:5518210] multipeer manager: start client restart timer: 0x17d8d270
2016-04-06 03:16:38.643 ThaliTest[2896:5518210] THEMultipeerManager initialized peer 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:7
2016-04-06 03:16:38.643 ThaliTest[2896:5518210] jxcore: startUpdateAdvertisingAndListening: success
ok 165 Can call startUpdateAdvertisingAndListeningwithout error
2016-04-06 03:16:38.644 ThaliTest[2896:5518210] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-04-06 03:16:38.644 ThaliTest[2896:5518210] jxcore: startListeningForAdvertisements: success
ok 166 Can call startListeningForAdvertisements without error
,2016-04-06 03:16:39.459 ThaliTest[2896:5518065] client: found new peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:6
,ok 167 peers must be an array
,ok 168 peers must not be zero-length
,ok 169 peer must have peerIdentifier
,ok 170 peerIdentifier must be a string
,ok 171 peer must have peerAvailable
,ok 172 peer must have pleaseConnect
,# teardown
,2016-04-06 03:16:39.743 ThaliTest[2896:5518065] client: found new peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:6
2016-04-06 03:16:39.746 ThaliTest[2896:5518065] client: found new peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:7
,2016-04-06 03:16:46.697 ThaliTest[2896:5518210] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-04-06 03:16:46.697 ThaliTest[2896:5518210] jxcore: stopListeningForAdvertisements: success
ok 173 Should be able to call stopListeningForAdvertisements in teardown
2016-04-06 03:16:46.698 ThaliTest[2896:5518210] jxcore: stopAdvertisingAndListening
,2016-04-06 03:16:46.698 ThaliTest[2896:5518210] THEMultipeerManager stopping peer
2016-04-06 03:16:46.699 ThaliTest[2896:5518210] multipeer manager: stop client timer
2016-04-06 03:16:46.699 ThaliTest[2896:5518210] jxcore: stopAdvertisingAndListening: success
ok 174 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 42. Can connect to a remote peer
,2016-04-06 03:16:46.989 ThaliTest[2896:5518210] jxcore: startUpdateAdvertisingAndListening
2016-04-06 03:16:46.989 ThaliTest[2896:5518210] server: starting 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
2016-04-06 03:16:46.989 ThaliTest[2896:5518210] multipeer m,anager: start client restart timer: 0x17d8d270
2016-04-06 03:16:46.990 ThaliTest[2896:5518210] THEMultipeerManager initialized peer 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8
2016-04-06 03:16:46.990 ThaliTest[2896:5518210] jxcore: startUpdateAdvertisingAndListening: success
ok 175 Can call startUpdateAdvertisingAndListening without error
2016-04-06 03:16:46.991 ThaliTest[2896:5518210] jxcore: startListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-04-06 03:16:46.991 ThaliTest[2896:5518210] jxcore: startListeningForAdvertisements: success
ok 176 Can call startListeningForAdvertisements without error
,2016-04-06 03:16:47.823 ThaliTest[2896:5518065] client: found new peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:7
2016-04-06 03:16:47.824 ThaliTest[2896:5518065] client: found new peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:7
2016-04-06 03:16:47.824 ThaliTest[2896:5518065] client: found new peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:7
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"8C5B19F5-9879-44C8-A20C-4970704F4B6A:7","pleaseConnect":0}]
2016,-04-06 03:16:47.826 ThaliTest[2896:5518210] jxcore: connect 8C5B19F5-9879-44C8-A20C-4970704F4B6A:7
2016-04-06 03:16:47.826 ThaliTest[2896:5518210] client: server will connect
2016-04-06 03:16:47.826 ThaliTest[2896:5518210] client session: reverseConnect
2016-04-06 03:16:47.826 ThaliTest[2896:5518210] client session: stateChange:0->1 8C5B19F5-9879-44C8-A20C-4970704F4B6A:7
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"C5E616F6-311E-4AAE-ABEF-071095D8F02C:7","pleaseConnect":0}]
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:7","pleaseConnect":0}]
,2016-04-06 03:16:49.234 ThaliTest[2896:5518065] multipeer session: reset timer
2016-04-06 03:16:49.234 ThaliTest[2896:5518065] server: rejecting invitation from BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76 due to previous generation (7DE50CBF-CC92-4CD5-AA12-B28CD,384766D:8 != 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:7)
,2016-04-06 03:16:49.313 ThaliTest[2896:5518992] client session: not connected 8C5B19F5-9879-44C8-A20C-4970704F4B6A:7
,2016-04-06 03:16:49.314 ThaliTest[2896:5518992] client session: onLinkFailure: 8C5B19F5-9879-44C8-A20C-4970704F4B6A
2016-04-06 03:16:49.314 ThaliTest[2896:5518992] client session: disconnect
2016-04-06 03:16:49.314 ThaliTest[2896:5518992] client session: stateChange:1->0 8C5B19F5-9879-44C8-A20C-4970704F4B6A:7
2016-04-06 03:16:49.315 ThaliTest[2896:5518992] client session: no connect callback (server initiated)
,2016-04-06 03:16:52.320 ThaliTest[2896:5518065] multipeer session: reset timer
2016-04-06 03:16:52.320 ThaliTest[2896:5518065] server: disconnecting to refresh session (BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76)
2016-04-06 03:16:52.320 ThaliTest[2896:5518065] server: rejecting invitation from BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76 due to previous generation (7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8 != 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:7)
,2016-04-06 03:16:55.461 ThaliTest[2896:5518065] multipeer session: reset timer
2016-04-06 03:16:55.461 ThaliTest[2896:5518065] server: disconnecting to refresh session (BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76)
2016-04-06 03:16:55.461 ThaliTest[2896:5518065] server: rejecting invitation from BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76 due to previous generation (7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8 != 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:7)
,2016-04-06 03:16:57.827 ThaliTest[2896:5518065] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect ret,ry - retries left: 9
,2016-04-06 03:16:58.555 ThaliTest[2896:5518065] multipeer session: reset timer
2016-04-06 03:16:58.556 ThaliTest[2896:5518065] server: disconnecting to refresh session (BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76)
2016-04-06 03:16:58.556 ThaliTest[2896:5518065] server: rejecting invitation from BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76 due to previous generation (7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8 != 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:7)
,2016-04-06 03:17:00.832 ThaliTest[2896:5518210] jxcore: connect 8C5B19F5-9879-44C8-A20C-4970704F4B6A:7
2016-04-06 03:17:00.832 ThaliTest[2896:5518210] client: server will connect
2016-04-06 03:17:00.832 ThaliTest[2896:5518210] client session: reverseConn,ect
2016-04-06 03:17:00.832 ThaliTest[2896:5518210] client session: stateChange:0->1 8C5B19F5-9879-44C8-A20C-4970704F4B6A:7
,2016-04-06 03:17:01.440 ThaliTest[2896:5518992] client session: not connected 8C5B19F5-9879-44C8-A20C-4970704F4B6A:7
2016-04-06 03:17:01.440 ThaliTest[2896:5518992] client session: onLinkFailure: 8C5B19F5-9879-44C8-A20C-4970704F4B6A
2016-04-06 03:17:01.440 ThaliTest[2896:5518992] client session: disconnect
,2016-04-06 03:17:01.440 ThaliTest[2896:5518992] client session: stateChange:1->0 8C5B19F5-9879-44C8-A20C-4970704F4B6A:7
2016-04-06 03:17:01.442 ThaliTest[2896:5518992] client session: no connect callback (server initiated)
,2016-04-06 03:17:01.743 ThaliTest[2896:5518065] multipeer session: reset timer
2016-04-06 03:17:01.743 ThaliTest[2896:5518065] server: disconnecting to refresh session (BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76)
2016-04-06 03:17:01.743 ThaliTest[2896:5518065], server: rejecting invitation from BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76 due to previous generation (7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8 != 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:7)
,2016-04-06 03:17:04.847 ThaliTest[2896:5518065] multipeer session: reset timer
2016-04-06 03:17:04.848 ThaliTest[2896:5518065] server: disconnecting to refresh session (BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76)
2016-04-06 03:17:04.848 ThaliTest[2896:5518065] server: rejecting invitation from BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76 due to previous generation (7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8 != 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:7)
,2016-04-06 03:17:06.990 ThaliTest[2896:5518065] multipeer manager: restart client
,2016-04-06 03:17:07.008 ThaliTest[2896:5518065] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:7
2016-04-06 03:17:07.008 ThaliTest[2896:5518065] client: found updated peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:8
2016-04-06 03:17:07.008 ThaliTest[2896:5518065] client: found updated peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:8","pleaseConne,ct":0}]
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"8C5B19F5-9879-44C8-A20C-4970704F4B6A:8","pleaseConnect":0}]
,2016-04-06 03:17:08.009 ThaliTest[2896:5518065] multipeer session: reset timer
2016-04-06 03:17:08.010 ThaliTest[2896:5518065] server: disconnecting to refresh session (BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76)
2016-04-06 03:17:08.010 ThaliTest[2896:5518065] server: rejecting invitation from BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76 due to previous generation (7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8 != 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:7)
,2016-04-06 03:17:10.833 ThaliTest[2896:5518065] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-04-06 03:17:11.186 ThaliTest[2896:5518065] multipeer session: reset timer
2016-04-06 03:17:11.186 ThaliTest[2896:5518065] server: disconnecting to refresh session (BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76)
2016-04-06 03:17:11.186 ThaliTest[2896:5518065] server: rejecting invitation from BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76 due to previous generation (7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8 != 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:7)
,2016-04-06 03:17:13.839 ThaliTest[2896:5518210] jxcore: connect 8C5B19F5-9879-44C8-A20C-4970704F4B6A:7
2016-04-06 03:17:13.840 ThaliTest[2896:5518210] client: server will connect
2016-04-06 03:17:13.840 ThaliTest[2896:5518210] client session: reverseConnect
2016-04-06 03:17:13.840 ThaliTest[2896:5518210] client session: stateChange:0->1 8C5B19F5-9879-44C8-A20C-4970704F4B6A:8
,2016-04-06 03:17:14.332 ThaliTest[2896:5518065] multipeer session: reset timer
2016-04-06 03:17:14.332 ThaliTest[2896:5518065] server: disconnecting to refresh session (BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76)
2016-04-06 03:17:14.332 ThaliTest[2896:5518065], server: rejecting invitation from BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76 due to previous generation (7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8 != 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:7)
,2016-04-06 03:17:14.866 ThaliTest[2896:5519122] client session: not connected 8C5B19F5-9879-44C8-A20C-4970704F4B6A:8
2016-04-06 03:17:14.866 ThaliTest[2896:5519122] client session: onLinkFailure: 8C5B19F5-9879-44C8-A20C-4970704F4B6A
2016-04-06 03:17:14.8,66 ThaliTest[2896:5519122] client session: disconnect
2016-04-06 03:17:14.866 ThaliTest[2896:5519122] client session: stateChange:1->0 8C5B19F5-9879-44C8-A20C-4970704F4B6A:8
2016-04-06 03:17:14.866 ThaliTest[2896:5519122] client session: no connect callback (server initiated)
,2016-04-06 03:17:17.492 ThaliTest[2896:5518065] multipeer session: reset timer
2016-04-06 03:17:17.492 ThaliTest[2896:5518065] server: disconnecting to refresh session (BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76)
2016-04-06 03:17:17.492 ThaliTest[2896:5518065] server: rejecting invitation from BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76 due to previous generation (7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8 != 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:7)
,2016-04-06 03:17:23.841 ThaliTest[2896:5518065] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-04-06 03:17:26.847 ThaliTest[2896:5518210] jxcore: connect 8C5B19F5-9879-44C8-A20C-4970704F4B6A:7
2016-04-06 03:17:26.848 ThaliTest[2896:5518210] client: server will connect
2016-04-06 03:17:26.848 ThaliTest[2896:5518210] client session: reverseConnect
2016-04-06 03:17:26.848 ThaliTest[2896:5518210] client session: stateChange:0->1 8C5B19F5-9879-44C8-A20C-4970704F4B6A:8
,2016-04-06 03:17:26.991 ThaliTest[2896:5518065] multipeer manager: restart client
,2016-04-06 03:17:27.010 ThaliTest[2896:5518065] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:8
2016-04-06 03:17:27.010 ThaliTest[2896:5518065] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:8
2016-04-06 03:17:27.010 ThaliTest[2896:5518065] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:7
,2016-04-06 03:17:36.849 ThaliTest[2896:5518065] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-04-06 03:17:39.860 ThaliTest[2896:5518210] jxcore: connect 8C5B19F5-9879-44C8-A20C-4970704F4B6A:7
2016-04-06 03:17:39.860 ThaliTest[2896:5518210] client: already connect(ing/ed) to 8C5B19F5-9879-44C8-A20C-4970704F4B6A:7
2016-04-06 03:17:39.860 Thali,Test[2896:5518210] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-04-06 03:17:42.869 ThaliTest[2896:5518210] jxcore: connect 8C5B19F5-9879-44C8-A20C-4970704F4B6A:7
2016-04-06 03:17:42.869 ThaliTest[2896:5518210] client: already connect(ing/ed) to 8C5B19F5-9879-44C8-A20C-4970704F4B6A:7
2016-04-06 03:17:42.869 ThaliTest[2896:5518210] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-04-06 03:17:45.875 ThaliTest[2896:5518210] jxcore: connect 8C5B19F5-9879-44C8-A20C-4970704F4B6A:7
2016-04-06 03:17:45.875 ThaliTest[2896:5518210] client: already connect(ing/ed) to 8C5B19F5-9879-44C8-A20C-4970704F4B6A:7
2016-04-06 03:17:45.875 Thali,Test[2896:5518210] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-04-06 03:17:46.991 ThaliTest[2896:5518065] multipeer manager: restart client
,2016-04-06 03:17:48.885 ThaliTest[2896:5518210] jxcore: connect 8C5B19F5-9879-44C8-A20C-4970704F4B6A:7
2016-04-06 03:17:48.885 ThaliTest[2896:5518210] client: already connect(ing/ed) to 8C5B19F5-9879-44C8-A20C-4970704F4B6A:7
2016-04-06 03:17:48.885 ThaliTest[2896:5518210] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-04-06 03:17:51.898 ThaliTest[2896:5518210] jxcore: connect 8C5B19F5-9879-44C8-A20C-4970704F4B6A:7
2016-04-06 03:17:51.898 ThaliTest[2896:5518210] client: already connect(ing/ed) to 8C5B19F5-9879-44C8-A20C-4970704F4B6A:7
2016-04-06 03:17:51.898 ThaliTest[2896:5518210] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-04-06 03:17:54.910 ThaliTest[2896:5518210] jxcore: connect 8C5B19F5-9879-44C8-A20C-4970704F4B6A:7
2016-04-06 03:17:54.910 ThaliTest[2896:5518210] client: already connect(ing/ed) to 8C5B19F5-9879-44C8-A20C-4970704F4B6A:7
2016-04-06 03:17:54.910 Thali,Test[2896:5518210] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
WARN testThaliMobileNative: Too many connect retries!
,not ok 177 Connect failed!
  ---
,    operator: fail
,  ...
,# teardown
,2016-04-06 03:17:59.852 ThaliTest[2896:5519162] client session: not connected 8C5B19F5-9879-44C8-A20C-4970704F4B6A:8
2016-04-06 03:17:59.853 ThaliTest[2896:5519162] client session: onLinkFailure: 8C5B19F5-9879-44C8-A20C-4970704F4B6A
2016-04-06 03:17:59.8,53 ThaliTest[2896:5519162] client session: disconnect
2016-04-06 03:17:59.853 ThaliTest[2896:5519162] client session: stateChange:1->0 8C5B19F5-9879-44C8-A20C-4970704F4B6A:8
2016-04-06 03:17:59.853 ThaliTest[2896:5519162] client session: no connect callback (server initiated)
,2016-04-06 03:18:00.018 ThaliTest[2896:5518065] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:8
2016-04-06 03:18:00.018 ThaliTest[2896:5518065] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:8
2016-04-06 03:18:00.01,9 ThaliTest[2896:5518065] client: found updated peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"C5E616F6-311E-4AAE-ABEF-071095D8F02C:8","pleaseConnect":0}]
,2016-04-06 03:18:06.990 ThaliTest[2896:5518065] multipeer manager: restart client
,2016-04-06 03:18:07.011 ThaliTest[2896:5518065] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:8
2016-04-06 03:18:07.013 ThaliTest[2896:5518065] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
2016-04-06 03:18:07.014 ThaliTest[2896:5518065] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:8
,2016-04-06 03:18:26.991 ThaliTest[2896:5518065] multipeer manager: restart client
,2016-04-06 03:18:27.012 ThaliTest[2896:5518065] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:8
2016-04-06 03:18:27.012 ThaliTest[2896:5518065] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
,2016-04-06 03:18:27.017 ThaliTest[2896:5518065] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:8
,2016-04-06 03:18:46.991 ThaliTest[2896:5518065] multipeer manager: restart client
,2016-04-06 03:18:47.007 ThaliTest[2896:5518065] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
2016-04-06 03:18:47.008 ThaliTest[2896:5518065] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:8
2016-04-06 03:18:47.008 ThaliTest[2896:5518065] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:8
,2016-04-06 03:18:55.708 ThaliTest[2896:5518210] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-04-06 03:18:55.709 ThaliTest[2896:5518210] jxcore: stopListeningForAdvertisements: success
,ok 178 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-06 03:18:55.711 ThaliTest[2896:5518210] jxcore: stopAdvertisingAndListening
2016-04-06 03:18:55.711 ThaliTest[2896:5518210] THEMultipeerManager stopping peer
2016-04-06 03:18:55.711 ThaliTest[2896:5518210] multipeer manager: stop client timer
2016-04-06 03:18:55.711 ThaliTest[2896:5518210] jxcore: stopAdvertisingAndListening: success
ok 179 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 43. Get error when trying to double connect to a peer
,2016-04-06 03:18:56.413 ThaliTest[2896:5518210] jxcore: startUpdateAdvertisingAndListening
2016-04-06 03:18:56.414 ThaliTest[2896:5518210] server: starting 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:18:56.414 ThaliTest[2896:5518210] multipeer m,anager: start client restart timer: 0x17d8d270
2016-04-06 03:18:56.414 ThaliTest[2896:5518210] THEMultipeerManager initialized peer 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9
2016-04-06 03:18:56.414 ThaliTest[2896:5518210] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 180 Can call startUpdateAdvertisingAndListening without error
2016-04-06 03:18:56.415 ThaliTest[2896:5518210] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-04-06 03:18:56.416 ThaliTest[2896:5518210] jxcore: startListeningForAdvertisements: success
ok 181 Can call startListeningForAdvertisements without error
,2016-04-06 03:18:57.291 ThaliTest[2896:5518065] client: found new peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
2016-04-06 03:18:57.291 ThaliTest[2896:5518065] client: found new peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:8
2016-04-06 03:18:57.292 ThaliTes,t[2896:5518065] client: found new peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:8
,2016-04-06 03:18:57.293 ThaliTest[2896:5518210] jxcore: connect C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
2016-04-06 03:18:57.297 ThaliTest[2896:5518210] client: server will connect
2016-04-06 03:18:57.297 ThaliTest[2896:5518210] client session: reverseConn,ect
2016-04-06 03:18:57.297 ThaliTest[2896:5518210] client session: stateChange:0->1 C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
,2016-04-06 03:18:57.795 ThaliTest[2896:5518065] multipeer session: reset timer
2016-04-06 03:18:57.795 ThaliTest[2896:5518065] server: rejecting invitation from C5E616F6-311E-4AAE-ABEF-071095D8F02C due to previous generation (7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9 != 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8)
,2016-04-06 03:18:58.054 ThaliTest[2896:5519308] client session: not connected C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
2016-04-06 03:18:58.054 ThaliTest[2896:5519308] client session: onLinkFailure: C5E616F6-311E-4AAE-ABEF-071095D8F02C
,2016-04-06 03:18:58.054 ThaliTest[2896:5519308] client session: disconnect
2016-04-06 03:18:58.055 ThaliTest[2896:5519308] client session: stateChange:1->0 C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
2016-04-06 03:18:58.056 ThaliTest[2896:5519308] client session: no connect callback (server initiated)
,2016-04-06 03:18:58.550 ThaliTest[2896:5518065] multipeer session: reset timer
,2016-04-06 03:18:58.550 ThaliTest[2896:5518065] server: rejecting invitation from BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76 due to previous generation (7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9 != 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8)
,2016-04-06 03:19:01.134 ThaliTest[2896:5518065] multipeer session: reset timer
2016-04-06 03:19:01.134 ThaliTest[2896:5518065] server: disconnecting to refresh session (C5E616F6-311E-4AAE-ABEF-071095D8F02C)
2016-04-06 03:19:01.135 ThaliTest[2896:5518065] server: rejecting invitation from C5E616F6-311E-4AAE-ABEF-071095D8F02C due to previous generation (7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9 != 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8)
,2016-04-06 03:19:02.167 ThaliTest[2896:5518065] multipeer session: reset timer
2016-04-06 03:19:02.167 ThaliTest[2896:5518065] server: disconnecting to refresh session (BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76)
2016-04-06 03:19:02.167 ThaliTest[2896:5518065] server: rejecting invitation from BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76 due to previous generation (7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9 != 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8)
,2016-04-06 03:19:04.359 ThaliTest[2896:5518065] multipeer session: reset timer
2016-04-06 03:19:04.360 ThaliTest[2896:5518065] server: disconnecting to refresh session (C5E616F6-311E-4AAE-ABEF-071095D8F02C)
2016-04-06 03:19:04.360 ThaliTest[2896:5518065] server: rejecting invitation from C5E616F6-311E-4AAE-ABEF-071095D8F02C due to previous generation (7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9 != 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8)
,2016-04-06 03:19:05.983 ThaliTest[2896:5518065] multipeer session: reset timer
2016-04-06 03:19:05.983 ThaliTest[2896:5518065] server: disconnecting to refresh session (BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76)
2016-04-06 03:19:05.983 ThaliTest[2896:5518065], server: rejecting invitation from BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76 due to previous generation (7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9 != 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8)
,2016-04-06 03:19:07.298 ThaliTest[2896:5518065] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-04-06 03:19:07.524 ThaliTest[2896:5518065] multipeer session: reset timer
2016-04-06 03:19:07.524 ThaliTest[2896:5518065] server: disconnecting to refresh session (C5E616F6-311E-4AAE-ABEF-071095D8F02C)
2016-04-06 03:19:07.524 ThaliTest[2896:5518065] server: rejecting invitation from C5E616F6-311E-4AAE-ABEF-071095D8F02C due to previous generation (7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9 != 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8)
,2016-04-06 03:19:09.636 ThaliTest[2896:5518065] multipeer session: reset timer
2016-04-06 03:19:09.636 ThaliTest[2896:5518065] server: disconnecting to refresh session (BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76)
2016-04-06 03:19:09.637 ThaliTest[2896:5518065] server: rejecting invitation from BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76 due to previous generation (7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9 != 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8)
,2016-04-06 03:19:10.307 ThaliTest[2896:5518210] jxcore: connect C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
2016-04-06 03:19:10.308 ThaliTest[2896:5518210] client: server will connect
2016-04-06 03:19:10.308 ThaliTest[2896:5518210] client session: reverseConnect
2016-04-06 03:19:10.308 ThaliTest[2896:5518210] client session: stateChange:0->1 C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
,2016-04-06 03:19:10.703 ThaliTest[2896:5518065] multipeer session: reset timer
2016-04-06 03:19:10.703 ThaliTest[2896:5518065] server: disconnecting to refresh session (C5E616F6-311E-4AAE-ABEF-071095D8F02C)
2016-04-06 03:19:10.703 ThaliTest[2896:5518065] server: rejecting invitation from C5E616F6-311E-4AAE-ABEF-071095D8F02C due to previous generation (7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9 != 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8)
,2016-04-06 03:19:10.714 ThaliTest[2896:5519307] client session: not connected C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
2016-04-06 03:19:10.714 ThaliTest[2896:5519307] client session: onLinkFailure: C5E616F6-311E-4AAE-ABEF-071095D8F02C
2016-04-06 03:19:10.714 ThaliTest[2896:5519307] client session: disconnect
2016-04-06 03:19:10.714 ThaliTest[2896:5519307] client session: stateChange:1->0 C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
2016-04-06 03:19:10.715 ThaliTest[2896:5519307] client session: no connect callback (server initiated)
,2016-04-06 03:19:12.746 ThaliTest[2896:5518065] multipeer session: reset timer
2016-04-06 03:19:12.746 ThaliTest[2896:5518065] server: disconnecting to refresh session (BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76)
2016-04-06 03:19:12.746 ThaliTest[2896:5518065] server: rejecting invitation from BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76 due to previous generation (7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9 != 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8)
,2016-04-06 03:19:13.803 ThaliTest[2896:5518065] multipeer session: reset timer
2016-04-06 03:19:13.804 ThaliTest[2896:5518065] server: disconnecting to refresh session (C5E616F6-311E-4AAE-ABEF-071095D8F02C)
2016-04-06 03:19:13.804 ThaliTest[2896:5518065], server: rejecting invitation from C5E616F6-311E-4AAE-ABEF-071095D8F02C due to previous generation (7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9 != 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8)
,2016-04-06 03:19:15.889 ThaliTest[2896:5518065] multipeer session: reset timer
2016-04-06 03:19:15.889 ThaliTest[2896:5518065] server: disconnecting to refresh session (BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76)
2016-04-06 03:19:15.890 ThaliTest[2896:5518065] server: rejecting invitation from BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76 due to previous generation (7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9 != 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8)
,2016-04-06 03:19:16.415 ThaliTest[2896:5518065] multipeer manager: restart client
,2016-04-06 03:19:16.436 ThaliTest[2896:5518065] client: found updated peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
2016-04-06 03:19:16.438 ThaliTest[2896:5518065] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
2016-04-06 03:19:16.438, ThaliTest[2896:5518065] client: found updated peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
,2016-04-06 03:19:16.994 ThaliTest[2896:5518065] multipeer session: reset timer
2016-04-06 03:19:16.994 ThaliTest[2896:5518065] server: disconnecting to refresh session (C5E616F6-311E-4AAE-ABEF-071095D8F02C)
2016-04-06 03:19:16.994 ThaliTest[2896:5518065] server: rejecting invitation from C5E616F6-311E-4AAE-ABEF-071095D8F02C due to previous generation (7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9 != 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8)
,2016-04-06 03:19:19.196 ThaliTest[2896:5518065] multipeer session: reset timer
2016-04-06 03:19:19.196 ThaliTest[2896:5518065] server: disconnecting to refresh session (BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76)
2016-04-06 03:19:19.197 ThaliTest[2896:5518065], server: rejecting invitation from BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76 due to previous generation (7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9 != 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8)
,2016-04-06 03:19:20.084 ThaliTest[2896:5518065] multipeer session: reset timer
2016-04-06 03:19:20.085 ThaliTest[2896:5518065] server: disconnecting to refresh session (C5E616F6-311E-4AAE-ABEF-071095D8F02C)
2016-04-06 03:19:20.085 ThaliTest[2896:5518065] server: rejecting invitation from C5E616F6-311E-4AAE-ABEF-071095D8F02C due to previous generation (7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9 != 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8)
,2016-04-06 03:19:20.309 ThaliTest[2896:5518065] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-04-06 03:19:22.281 ThaliTest[2896:5518065] multipeer session: reset timer
2016-04-06 03:19:22.281 ThaliTest[2896:5518065] server: disconnecting to refresh session (BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76)
2016-04-06 03:19:22.281 ThaliTest[2896:5518065] server: rejecting invitation from BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76 due to previous generation (7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9 != 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8)
,2016-04-06 03:19:23.229 ThaliTest[2896:5518065] multipeer session: reset timer
2016-04-06 03:19:23.229 ThaliTest[2896:5518065] server: disconnecting to refresh session (C5E616F6-311E-4AAE-ABEF-071095D8F02C)
2016-04-06 03:19:23.229 ThaliTest[2896:5518065] server: rejecting invitation from C5E616F6-311E-4AAE-ABEF-071095D8F02C due to previous generation (7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9 != 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8)
,2016-04-06 03:19:23.319 ThaliTest[2896:5518210] jxcore: connect C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
2016-04-06 03:19:23.320 ThaliTest[2896:5518210] client: server will connect
2016-04-06 03:19:23.320 ThaliTest[2896:5518210] client session: reverseConn,ect
2016-04-06 03:19:23.320 ThaliTest[2896:5518210] client session: stateChange:0->1 C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
,2016-04-06 03:19:23.761 ThaliTest[2896:5519308] client session: not connected C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
2016-04-06 03:19:23.761 ThaliTest[2896:5519308] client session: onLinkFailure: C5E616F6-311E-4AAE-ABEF-071095D8F02C
2016-04-06 03:19:23.7,61 ThaliTest[2896:5519308] client session: disconnect
2016-04-06 03:19:23.761 ThaliTest[2896:5519308] client session: stateChange:1->0 C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
2016-04-06 03:19:23.762 ThaliTest[2896:5519308] client session: no connect callback (server initiated)
,2016-04-06 03:19:25.377 ThaliTest[2896:5518065] multipeer session: reset timer
2016-04-06 03:19:25.377 ThaliTest[2896:5518065] server: disconnecting to refresh session (BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76)
2016-04-06 03:19:25.377 ThaliTest[2896:5518065] server: rejecting invitation from BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76 due to previous generation (7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9 != 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8)
,2016-04-06 03:19:26.424 ThaliTest[2896:5518065] multipeer session: reset timer
2016-04-06 03:19:26.424 ThaliTest[2896:5518065] server: disconnecting to refresh session (C5E616F6-311E-4AAE-ABEF-071095D8F02C)
2016-04-06 03:19:26.424 ThaliTest[2896:5518065] server: rejecting invitation from C5E616F6-311E-4AAE-ABEF-071095D8F02C due to previous generation (7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9 != 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8)
,2016-04-06 03:19:28.978 ThaliTest[2896:5518065] multipeer session: reset timer
,2016-04-06 03:19:28.978 ThaliTest[2896:5518065] server: disconnecting to refresh session (BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76)
2016-04-06 03:19:28.979 ThaliTest[2896:5518065] server: rejecting invitation from BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76 due to p,revious generation (7DE50CBF-CC92-4CD5-AA12-B28CD384766D:9 != 7DE50CBF-CC92-4CD5-AA12-B28CD384766D:8)
,2016-04-06 03:19:33.321 ThaliTest[2896:5518065] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-04-06 03:19:36.335 ThaliTest[2896:5518210] jxcore: connect C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
2016-04-06 03:19:36.335 ThaliTest[2896:5518210] client: server will connect
2016-04-06 03:19:36.336 ThaliTest[2896:5518210] client session: reverseConnect
2016-04-06 03:19:36.336 ThaliTest[2896:5518210] client session: stateChange:0->1 C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
,2016-04-06 03:19:36.415 ThaliTest[2896:5518065] multipeer manager: restart client
,2016-04-06 03:19:36.433 ThaliTest[2896:5518065] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
2016-04-06 03:19:36.434 ThaliTest[2896:5518065] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
2016-04-06 03:19:36.434 ThaliTest[2896:5518065] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
,2016-04-06 03:19:46.337 ThaliTest[2896:5518065] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 6
,2016-04-06 03:19:49.347 ThaliTest[2896:5518210] jxcore: connect C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
2016-04-06 03:19:49.348 ThaliTest[2896:5518210] client: already connect(ing/ed) to C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
2016-04-06 03:19:49.348 Thali,Test[2896:5518210] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-04-06 03:19:52.354 ThaliTest[2896:5518210] jxcore: connect C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
2016-04-06 03:19:52.354 ThaliTest[2896:5518210] client: already connect(ing/ed) to C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
2016-04-06 03:19:52.354 ThaliTest[2896:5518210] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-04-06 03:19:55.370 ThaliTest[2896:5518210] jxcore: connect C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
2016-04-06 03:19:55.370 ThaliTest[2896:5518210] client: already connect(ing/ed) to C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
2016-04-06 03:19:55.370 Thali,Test[2896:5518210] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-04-06 03:19:56.415 ThaliTest[2896:5518065] multipeer manager: restart client
,2016-04-06 03:19:56.431 ThaliTest[2896:5518065] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
2016-04-06 03:19:56.431 ThaliTest[2896:5518065] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
2016-04-06 03:19:56.431 ThaliTest[2896:5518065] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
,2016-04-06 03:19:58.382 ThaliTest[2896:5518210] jxcore: connect C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
2016-04-06 03:19:58.382 ThaliTest[2896:5518210] client: already connect(ing/ed) to C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
2016-04-06 03:19:58.382 Thali,Test[2896:5518210] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-04-06 03:20:01.385 ThaliTest[2896:5518210] jxcore: connect C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
2016-04-06 03:20:01.385 ThaliTest[2896:5518210] client: already connect(ing/ed) to C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
2016-04-06 03:20:01.385 ThaliTest[2896:5518210] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-04-06 03:20:04.392 ThaliTest[2896:5518210] jxcore: connect C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
2016-04-06 03:20:04.393 ThaliTest[2896:5518210] client: already connect(ing/ed) to C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
2016-04-06 03:20:04.393 ThaliTest[2896:5518210] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
WARN testThaliMobileNative: Too many connect retries!
,2016-04-06 03:20:09.330 ThaliTest[2896:5519483] client session: not connected C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
2016-04-06 03:20:09.330 ThaliTest[2896:5519483] client session: onLinkFailure: C5E616F6-311E-4AAE-ABEF-071095D8F02C
2016-04-06 03:20:09.3,30 ThaliTest[2896:5519483] client session: disconnect
2016-04-06 03:20:09.330 ThaliTest[2896:5519483] client session: stateChange:1->0 C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
2016-04-06 03:20:09.330 ThaliTest[2896:5519483] client session: no connect callback (server initiated)
,2016-04-06 03:20:16.415 ThaliTest[2896:5518065] multipeer manager: restart client
,2016-04-06 03:20:16.436 ThaliTest[2896:5518065] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
2016-04-06 03:20:16.437 ThaliTest[2896:5518065] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
,2016-04-06 03:20:16.444 ThaliTest[2896:5518065] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
,2016-04-06 03:20:36.415 ThaliTest[2896:5518065] multipeer manager: restart client
,2016-04-06 03:20:36.432 ThaliTest[2896:5518065] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
2016-04-06 03:20:36.433 ThaliTest[2896:5518065] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
2016-04-06 03:20:36.433 ThaliTest[2896:5518065] client: found updated peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
2016-04-06 03:20:36.434 ThaliTest[2896:5518210] jxcore: connect C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
2016-04-06 03:20:36.434 ThaliTest[2896:5518210] client: se,rver will connect
2016-04-06 03:20:36.434 ThaliTest[2896:5518210] client session: reverseConnect
2016-04-06 03:20:36.434 ThaliTest[2896:5518210] client session: stateChange:0->1 C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
,2016-04-06 03:20:37.482 ThaliTest[2896:5518065] multipeer session: reset timer
2016-04-06 03:20:37.482 ThaliTest[2896:5518065] server: disconnecting to refresh session (C5E616F6-311E-4AAE-ABEF-071095D8F02C)
2016-04-06 03:20:37.483 ThaliTest[2896:5518065], server session: connect
2016-04-06 03:20:37.483 ThaliTest[2896:5518065] server session: stateChange:0->1 C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
,2016-04-06 03:20:37.487 ThaliTest[2896:5518065] server: accepting invitation C5E616F6-311E-4AAE-ABEF-071095D8F02C
,2016-04-06 03:20:37.513 ThaliTest[2896:5519546] client session: not connected C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
2016-04-06 03:20:37.513 ThaliTest[2896:5519546] client session: onLinkFailure: C5E616F6-311E-4AAE-ABEF-071095D8F02C
2016-04-06 03:20:37.513 ThaliTest[2896:5519546] client session: disconnect
2016-04-06 03:20:37.513 ThaliTest[2896:5519546] client session: stateChange:1->0 C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
2016-04-06 03:20:37.513 ThaliTest[2896:5519546] client session: no connect callback (server initiated)
,2016-04-06 03:20:38.936 ThaliTest[2896:5519548] server session: p2p link connected
,2016-04-06 03:20:39.147 ThaliTest[2896:5518065] server relay: connected (to port: 59917)
2016-04-06 03:20:39.148 ThaliTest[2896:5518065] server session: stateChange:1->2 C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
2016-04-06 03:20:39.148 ThaliTest[2896:5518065] jxcore: connect: success
,2016-04-06 03:20:56.415 ThaliTest[2896:5518065] multipeer manager: restart client
,2016-04-06 03:20:56.431 ThaliTest[2896:5518065] client: found updated peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
2016-04-06 03:20:56.433 ThaliTest[2896:5518065] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
2016-04-06 03:20:56.434 ThaliTest[2896:5518065] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
,2016-04-06 03:20:56.435 ThaliTest[2896:5518210] jxcore: connect C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
2016-04-06 03:20:56.437 ThaliTest[2896:5518210] client: server already connected
2016-04-06 03:20:56.437 ThaliTest[2896:5518210] jxcore: connect: success
,2016-04-06 03:21:16.415 ThaliTest[2896:5518065] multipeer manager: restart client
,2016-04-06 03:21:16.432 ThaliTest[2896:5518065] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
2016-04-06 03:21:16.433 ThaliTest[2896:5518065] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
2016-04-06 03:21:16.433 ThaliTest[2896:5518065] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
,2016-04-06 03:21:36.415 ThaliTest[2896:5518065] multipeer manager: restart client
,2016-04-06 03:21:36.436 ThaliTest[2896:5518065] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
2016-04-06 03:21:36.437 ThaliTest[2896:5518065] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
2016-04-06 03:21:36.437 ThaliTest[2896:5518065] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
,2016-04-06 03:21:56.415 ThaliTest[2896:5518065] multipeer manager: restart client
,2016-04-06 03:21:56.432 ThaliTest[2896:5518065] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
2016-04-06 03:21:56.432 ThaliTest[2896:5518065] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
2016-04-06 03:21:56.432 ThaliTest[2896:5518065] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
,2016-04-06 03:22:16.414 ThaliTest[2896:5518065] multipeer manager: restart client
,2016-04-06 03:22:16.430 ThaliTest[2896:5518065] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
2016-04-06 03:22:16.430 ThaliTest[2896:5518065] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
,2016-04-06 03:22:16.432 ThaliTest[2896:5518065] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
,2016-04-06 03:22:36.415 ThaliTest[2896:5518065] multipeer manager: restart client
,2016-04-06 03:22:36.430 ThaliTest[2896:5518065] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
,2016-04-06 03:22:36.430 ThaliTest[2896:5518065] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
2016-04-06 03:22:36.432 ThaliTest[2896:5518065] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
,2016-04-06 03:22:56.415 ThaliTest[2896:5518065] multipeer manager: restart client
,2016-04-06 03:22:56.431 ThaliTest[2896:5518065] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
2016-04-06 03:22:56.432 ThaliTest[2896:5518065] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
2016-04-06 03:22:56.432 ThaliTest[2896:5518065] client: found updated peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
2016-04-06 03:22:56.433 ThaliTest[2896:5518210] jxcore: connect C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
2016-04-06 03:22:56.434 ThaliTest[2896:5518210] client: server already connected
2016-04-06 03:22:56.434 ThaliTest[2896:5518210] jxcore: connect: success
,2016-04-06 03:23:16.415 ThaliTest[2896:5518065] multipeer manager: restart client
,2016-04-06 03:23:16.433 ThaliTest[2896:5518065] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
2016-04-06 03:23:16.433 ThaliTest[2896:5518065] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
2016-04-06 03:23:16.433 ThaliTest[2896:5518065] client: found updated peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
2016-04-06 03:23:16.434 ThaliTest[2896:5518210] jxcore: connect C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
,2016-04-06 03:23:16.434 ThaliTest[2896:5518210] client: server already connected
2016-04-06 03:23:16.437 ThaliTest[2896:5518210] jxcore: connect: success
,2016-04-06 03:23:36.415 ThaliTest[2896:5518065] multipeer manager: restart client
,2016-04-06 03:23:36.429 ThaliTest[2896:5518065] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
2016-04-06 03:23:36.429 ThaliTest[2896:5518065] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
,2016-04-06 03:23:36.431 ThaliTest[2896:5518065] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
,2016-04-06 03:23:56.415 ThaliTest[2896:5518065] multipeer manager: restart client
,2016-04-06 03:23:56.431 ThaliTest[2896:5518065] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
,2016-04-06 03:23:56.433 ThaliTest[2896:5518065] client: found updated peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
2016-04-06 03:23:56.434 ThaliTest[2896:5518065] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
2016-04-06 03:23:56.435 ThaliTest[2896:5518210] jxcore: connect C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
2016-04-06 03:23:56.435 ThaliTest[2896:5518210] client: server already connected
2016-04-06 03:23:56.435 ThaliTest[2896:5518210] jxcore: connect: success
,2016-04-06 03:24:16.415 ThaliTest[2896:5518065] multipeer manager: restart client
,2016-04-06 03:24:16.430 ThaliTest[2896:5518065] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
,2016-04-06 03:24:16.432 ThaliTest[2896:5518065] client: found updated peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
2016-04-06 03:24:16.433 ThaliTest[2896:5518065] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
2016-04-06 03:24:16.433 ThaliTest[2896:5518210] jxcore: connect C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
2016-04-06 03:24:16.434 ThaliTest[2896:5518210] client: server already connected
2016-04-06 03:24:16.434 ThaliTest[2896:5518210] jxcore: connect: success
,2016-04-06 03:24:36.415 ThaliTest[2896:5518065] multipeer manager: restart client
,2016-04-06 03:24:36.434 ThaliTest[2896:5518065] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
2016-04-06 03:24:36.434 ThaliTest[2896:5518065] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
2016-04-06 03:24:36.435 ThaliTest[2896:5518065] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
,2016-04-06 03:24:56.415 ThaliTest[2896:5518065] multipeer manager: restart client
,2016-04-06 03:24:56.433 ThaliTest[2896:5518065] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
2016-04-06 03:24:56.433 ThaliTest[2896:5518065] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
2016-04-06 03:24:56.433 ThaliTest[2896:5518065] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
,2016-04-06 03:25:16.415 ThaliTest[2896:5518065] multipeer manager: restart client
,2016-04-06 03:25:16.430 ThaliTest[2896:5518065] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
2016-04-06 03:25:16.431 ThaliTest[2896:5518065] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
,2016-04-06 03:25:16.434 ThaliTest[2896:5518065] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
,2016-04-06 03:25:36.415 ThaliTest[2896:5518065] multipeer manager: restart client
,2016-04-06 03:25:56.415 ThaliTest[2896:5518065] multipeer manager: restart client
,2016-04-06 03:25:56.429 ThaliTest[2896:5518065] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
2016-04-06 03:25:56.429 ThaliTest[2896:5518065] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
,2016-04-06 03:25:56.435 ThaliTest[2896:5518065] client: found updated peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
2016-04-06 03:25:56.436 ThaliTest[2896:5518210] jxcore: connect C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
,2016-04-06 03:25:56.436 ThaliTest[2896:5518210] client: server already connected
2016-04-06 03:25:56.437 ThaliTest[2896:5518210] jxcore: connect: success
,2016-04-06 03:26:16.415 ThaliTest[2896:5518065] multipeer manager: restart client
,2016-04-06 03:26:16.432 ThaliTest[2896:5518065] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
2016-04-06 03:26:16.432 ThaliTest[2896:5518065] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
,2016-04-06 03:26:16.434 ThaliTest[2896:5518065] client: found updated peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
2016-04-06 03:26:16.435 ThaliTest[2896:5518210] jxcore: connect C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
2016-04-06 03:26:16.436 ThaliTest[28,96:5518210] client: server already connected
2016-04-06 03:26:16.436 ThaliTest[2896:5518210] jxcore: connect: success
,2016-04-06 03:26:36.415 ThaliTest[2896:5518065] multipeer manager: restart client
,2016-04-06 03:26:36.435 ThaliTest[2896:5518065] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
2016-04-06 03:26:36.435 ThaliTest[2896:5518065] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
,2016-04-06 03:26:36.444 ThaliTest[2896:5518065] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
,2016-04-06 03:26:56.415 ThaliTest[2896:5518065] multipeer manager: restart client
,2016-04-06 03:26:56.431 ThaliTest[2896:5518065] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
2016-04-06 03:26:56.431 ThaliTest[2896:5518065] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
,2016-04-06 03:26:56.441 ThaliTest[2896:5518065] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
,2016-04-06 03:27:16.415 ThaliTest[2896:5518065] multipeer manager: restart client
,2016-04-06 03:27:16.431 ThaliTest[2896:5518065] client: found updated peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
2016-04-06 03:27:16.431 ThaliTest[2896:5518065] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
2016-04-06 03:27:16.431, ThaliTest[2896:5518065] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
2016-04-06 03:27:16.432 ThaliTest[2896:5518210] jxcore: connect C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
2016-04-06 03:27:16.432 ThaliTest[2896:5518210] client: server already connected
2016-04-06 03:27:16.432 ThaliTest[2896:5518210] jxcore: connect: success
,2016-04-06 03:27:36.415 ThaliTest[2896:5518065] multipeer manager: restart client
,2016-04-06 03:27:36.431 ThaliTest[2896:5518065] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
2016-04-06 03:27:36.431 ThaliTest[2896:5518065] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
2016-04-06 03:27:36.431 ThaliTest[2896:5518065] client: found updated peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
,2016-04-06 03:27:36.434 ThaliTest[2896:5518210] jxcore: connect C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
2016-04-06 03:27:36.434 ThaliTest[2896:5518210] client: server already connected
2016-04-06 03:27:36.435 ThaliTest[2896:5518210] jxcore: connect: succe,ss
,2016-04-06 03:27:56.415 ThaliTest[2896:5518065] multipeer manager: restart client
,2016-04-06 03:27:56.433 ThaliTest[2896:5518065] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
2016-04-06 03:27:56.433 ThaliTest[2896:5518065] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
2016-04-06 03:27:56.434 ThaliTest[2896:5518065] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
,2016-04-06 03:28:16.415 ThaliTest[2896:5518065] multipeer manager: restart client
,2016-04-06 03:28:16.433 ThaliTest[2896:5518065] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
2016-04-06 03:28:16.433 ThaliTest[2896:5518065] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
2016-04-06 03:28:16.434 ThaliTest[2896:5518065] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
,2016-04-06 03:28:36.415 ThaliTest[2896:5518065] multipeer manager: restart client
,2016-04-06 03:28:36.430 ThaliTest[2896:5518065] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
2016-04-06 03:28:36.431 ThaliTest[2896:5518065] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
2016-04-06 03:28:36.431 ThaliTest[2896:5518065] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
,2016-04-06 03:28:56.415 ThaliTest[2896:5518065] multipeer manager: restart client
,2016-04-06 03:28:56.432 ThaliTest[2896:5518065] client: found updated peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
2016-04-06 03:28:56.432 ThaliTest[2896:5518065] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
2016-04-06 03:28:56.433 ThaliTest[2896:5518065] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
2016-04-06 03:28:56.433 ThaliTest[2896:5518210] jxcore: connect C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
2016-04-06 03:28:56.434 ThaliTest[2896:5518210] client: se,rver already connected
2016-04-06 03:28:56.434 ThaliTest[2896:5518210] jxcore: connect: success
,2016-04-06 03:29:16.415 ThaliTest[2896:5518065] multipeer manager: restart client
,2016-04-06 03:29:16.430 ThaliTest[2896:5518065] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
2016-04-06 03:29:16.430 ThaliTest[2896:5518065] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
,2016-04-06 03:29:16.433 ThaliTest[2896:5518065] client: found updated peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
2016-04-06 03:29:16.433 ThaliTest[2896:5518210] jxcore: connect C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
2016-04-06 03:29:16.434 ThaliTest[2896:5518210] client: server already connected
2016-04-06 03:29:16.434 ThaliTest[2896:5518210] jxcore: connect: success
,2016-04-06 03:29:36.415 ThaliTest[2896:5518065] multipeer manager: restart client
,2016-04-06 03:29:36.430 ThaliTest[2896:5518065] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
2016-04-06 03:29:36.431 ThaliTest[2896:5518065] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
2016-04-06 03:29:36.431 ThaliTest[2896:5518065] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
,2016-04-06 03:29:56.415 ThaliTest[2896:5518065] multipeer manager: restart client
,2016-04-06 03:29:56.431 ThaliTest[2896:5518065] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
2016-04-06 03:29:56.431 ThaliTest[2896:5518065] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
2016-04-06 03:29:56.432 ThaliTest[2896:5518065] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
,2016-04-06 03:30:16.415 ThaliTest[2896:5518065] multipeer manager: restart client
,2016-04-06 03:30:16.430 ThaliTest[2896:5518065] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
,2016-04-06 03:30:16.432 ThaliTest[2896:5518065] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
2016-04-06 03:30:16.433 ThaliTest[2896:5518065] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
,2016-04-06 03:30:36.415 ThaliTest[2896:5518065] multipeer manager: restart client
,2016-04-06 03:30:36.428 ThaliTest[2896:5518065] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
,2016-04-06 03:30:36.434 ThaliTest[2896:5518065] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
2016-04-06 03:30:36.434 ThaliTest[2896:5518065] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
,2016-04-06 03:30:56.415 ThaliTest[2896:5518065] multipeer manager: restart client
,2016-04-06 03:30:56.431 ThaliTest[2896:5518065] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:8
2016-04-06 03:30:56.431 ThaliTest[2896:5518065] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
2016-04-06 03:30:56.43,2 ThaliTest[2896:5518065] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
,2016-04-06 03:31:16.415 ThaliTest[2896:5518065] multipeer manager: restart client
,2016-04-06 03:31:16.431 ThaliTest[2896:5518065] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9
2016-04-06 03:31:16.431 ThaliTest[2896:5518065] client: found updated peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
2016-04-06 03:31:16.431, ThaliTest[2896:5518065] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
2016-04-06 03:31:16.432 ThaliTest[2896:5518210] jxcore: connect C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
2016-04-06 03:31:16.433 ThaliTest[2896:5518210] client: server already connected
2016-04-06 03:31:16.433 ThaliTest[2896:5518210] jxcore: connect: success
,2016-04-06 03:31:36.415 ThaliTest[2896:5518065] multipeer manager: restart client
,2016-04-06 03:31:36.438 ThaliTest[2896:5518065] client: found existing peer: 8C5B19F5-9879-44C8-A20C-4970704F4B6A:9
2016-04-06 03:31:36.438 ThaliTest[2896:5518065] client: found existing peer: C5E616F6-311E-4AAE-ABEF-071095D8F02C:9
2016-04-06 03:31:36.438 ThaliTest[2896:5518065] client: found existing peer: BA9EDD0A-C19B-44DC-B46A-4F5B1C971E76:9

```
