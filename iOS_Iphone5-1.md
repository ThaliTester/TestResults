#### Test 6480993629f6128_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/6480993629f6128/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/BD8F4387-CFBF-41A4-9855-082D1ED3BBB1/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/BD8F4387-CFBF-41A4-9855-082D1ED3BBB1/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/6480993629f6128/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/6480993629f6128/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/2F7B7CE5-23EE-416B-8390-34B26AEF380F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50395"
,(lldb)     command script import "/tmp/BD8F4387-CFBF-41A4-9855-082D1ED3BBB1/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-04-01 23:46:45.300 ThaliTest[2037:5160971] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/270EBED5-16DC-4C56-89C7-7A3399469F85/Library/Cookies/Cookies.binarycookies
,2016-04-01 23:46:45.408 ThaliTest[2037:5160971] Apache Cordova native platform version 4.1.0 is starting.
,2016-04-01 23:46:45.410 ThaliTest[2037:5160971] Multi-tasking -> Device: YES, App: YES
,2016-04-01 23:46:45.428 ThaliTest[2037:5160971] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-04-01 23:46:46.608 ThaliTest[2037:5160971] Using UIWebView
2016-04-01 23:46:46.611 ThaliTest[2037:5160971] [CDVTimer][handleopenurl] 0.299037ms
,2016-04-01 23:46:46.617 ThaliTest[2037:5160971] [CDVTimer][intentandnavigationfilter] 5.536020ms
2016-04-01 23:46:46.618 ThaliTest[2037:5160971] [CDVTimer][gesturehandler] 0.258029ms
2016-04-01 23:46:46.618 ThaliTest[2037:5160971] [CDVTimer][TotalPluginStartup] 6.908953ms
,2016-04-01 23:46:51.640 ThaliTest[2037:5160971] Resetting plugins due to page load.
,2016-04-01 23:46:53.790 ThaliTest[2037:5160971] Finished load of: file:///var/mobile/Containers/Bundle/Application/2F7B7CE5-23EE-416B-8390-34B26AEF380F/ThaliTest.app/www/index.html
,2016-04-01 23:46:53.979 ThaliTest[2037:5160971] JXcore Cordova plugin initializing
2016-04-01 23:46:53.980 ThaliTest[2037:5161122] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-04-01 23:47:08.222 ThaliTest[2037:5161122] jxcore: didRegisterToNative peerAvailabilityChanged
2016-04-01 23:47:08.222 ThaliTest[2037:5161122] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-04-01 23:47:08.223 ThaliTest[2037:5,161122] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-04-01 23:47:08.225 ThaliTest[2037:5161122] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5-1
WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2F7B7CE5-23EE-416B-8390-34B26AEF380F/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2F7B7CE5-23EE-416B-8390-34B26AEF380F/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2F7B7CE5-23EE-416B-8390-34B26AEF380F/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2F7B7CE5-23EE-416B-8390-34B26AEF380F/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2F7B7CE5-23EE-416B-8390-34B26AEF380F/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2F7B7CE5-23EE-416B-8390-34B26AEF380F/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2F7B7CE5-23EE-416B-8390-34B26AEF380F/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2F7B7CE5-23EE-416B-8390-34B26AEF380F/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2F7B7CE5-23EE-416B-8390-34B26AEF380F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2F7B7CE5-23EE-416B-8390-34B26AEF380F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2F7B7CE5-23EE-416B-8390-34B26AEF380F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2F7B7CE5-23EE-416B-8390-34B26AEF380F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2F7B7CE5-23EE-416B-8390-34B26AEF380F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2F7B7CE5-23EE-416B-8390-34B26AEF380F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2F7B7CE5-23EE-416B-8390-34B26AEF380F/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2F7B7CE5-23EE-416B-8390-34B26AEF380F/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2F7B7CE5-23EE-416B-8390-34B26AEF380F/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2F7B7CE5-23EE-416B-8390-34B26AEF380F/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2F7B7CE5-23EE-416B-8390-34B26AEF380F/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2F7B7CE5-23EE-416B-8390-34B26AEF380F/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2F7B7CE5-23EE-416B-8390-34B26AEF380F/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2F7B7CE5-23EE-416B-8390-34B26AEF380F/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 57766
,ok 1 Should throw
,# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 57768
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,ok 2 initial connection state should be CONNECTED
,DEBUG createNativeListener: incoming socket close
,ok 3 final connection state should be DISCONNECTED
,# teardown
,# setup
,# 3. emits routerPortConnectionFailed
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 57771
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
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
# setup
DEBUG createNativeListener: incoming socket close
,# 4. native server connections all up
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 57775
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
DEBUG createNativeListener: incoming socket close
,# 5. native server - closing incoming stream cleans outgoing socket
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 57780
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
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
,DEBUG createNativeListener: listening 57784
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 14 we should not have gotten an error
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
DEBUG createNativeListener: listening 57788
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
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
DEBUG createNativeListener: listening 57792
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
ok 20 we should not have gotten an error
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
DEBUG createNativeListener: listening 57796
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
,DEBUG createNativeListener: new mux
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
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
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
,DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: stream close:
DEBUG createNativeListener: mux close
DEBUG createNativeListener: stream close:
DEBUG createNativeListener: stream close:
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
DEBUG createNativeListener: listening 57848
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,ok 31 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
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
DEBUG createNativeListener: listening 57852
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
,# teardown
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
ok 83, participant data matches
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
DEBUG createNativeListener: listening 57862
,2016-04-01 23:50:18.155 ThaliTest[2037:5161122] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 23:50:18.156 ThaliTest[2037:5161122] jxcore: stopListeningForAdvertisements: success
ok 91 error should be null
ok 92 error should be null
2016-04-01 23:50:18.159 ThaliTest[2037:5161122] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUp,dateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 23:50:18.160 ThaliTest[2037:5161122] jxcore: stopListeningForAdvertisements: success
,ok 93 error should be null
ok 94 error should be null
,# teardown
,2016-04-01 23:50:18.348 ThaliTest[2037:5161122] jxcore: stopAdvertisingAndListening
2016-04-01 23:50:18.348 ThaliTest[2037:5161122] THEMultipeerManager stopping peer
2016-04-01 23:50:18.348 ThaliTest[2037:5161122] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-01 23:50:18.348 ThaliTest[2037:5161122] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 23:50:18.349 ThaliTest[2037:5161122] jxcore: stopListeningForAdvertisements: success
ok 95 error should be null
,ok 96 error should be null
# setup
,# 26. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 57864
2016-04-01 23:50:18.550 ThaliTest[2037:5161122] jxcore: startListeningForAdvertisements
,2016-04-01 23:50:18.553 ThaliTest[2037:5161122] multipeer manager: start client restart timer: 0x15ecd0d0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-01 23:50:18.554 ThaliTest[2037:5161122] jxcore: startListeningForAdvertisements: success
,ok 97 error should be null
ok 98 error should be null
2016-04-01 23:50:18.571 ThaliTest[2037:5161122] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-01 23:50:18.572 ThaliTest[2037:5161122] jxcore: startListeningForAdvertisements: success
ok 99 error should be null
ok 100 error should be null
# teardown
,2016-04-01 23:50:19.425 ThaliTest[2037:5161122] jxcore: stopAdvertisingAndListening
2016-04-01 23:50:19.426 ThaliTest[2037:5161122] THEMultipeerManager stopping peer
2016-04-01 23:50:19.426 ThaliTest[2037:5161122] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-01 23:50:19.426 ThaliTest[2037:5161122] jxcore: stopListeningForAdvertisements
2016-04-01 23:50:19.426 ThaliTest[2037:5161122] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-04-01 23:50:19.428 ThaliTest[2037:5161122] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 101 error should be null
ok 102 error should be null
# setup
,# 27. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 57866
,2016-04-01 23:50:37.726 ThaliTest[2037:5161122] jxcore: startUpdateAdvertisingAndListening
,2016-04-01 23:50:37.727 ThaliTest[2037:5161122] server: starting 53FC597F-8F79-47DA-ABAE-0C427F412EFF:1
,2016-04-01 23:50:37.728 ThaliTest[2037:5161122] multipeer manager: start client restart timer: 0x15ecd0d0
,2016-04-01 23:50:37.736 ThaliTest[2037:5161122] THEMultipeerManager initialized peer 53FC597F-8F79-47DA-ABAE-0C427F412EFF:1
,2016-04-01 23:50:37.737 ThaliTest[2037:5161122] jxcore: startUpdateAdvertisingAndListening: success
,ok 103 error should be null
,ok 104 error should be null
,2016-04-01 23:50:37.800 ThaliTest[2037:5161122] jxcore: startUpdateAdvertisingAndListening
,2016-04-01 23:50:37.801 ThaliTest[2037:5161122] THEMultipeerManager stopping peer
,2016-04-01 23:50:37.803 ThaliTest[2037:5161122] multipeer manager: stop client timer
,2016-04-01 23:50:37.806 ThaliTest[2037:5161122] server: starting 53FC597F-8F79-47DA-ABAE-0C427F412EFF:2
,2016-04-01 23:50:37.808 ThaliTest[2037:5161122] multipeer manager: start client restart timer: 0x15ecd0d0
,2016-04-01 23:50:37.811 ThaliTest[2037:5161122] THEMultipeerManager initialized peer 53FC597F-8F79-47DA-ABAE-0C427F412EFF:2
,2016-04-01 23:50:37.816 ThaliTest[2037:5161122] jxcore: startUpdateAdvertisingAndListening: success
,ok 105 error should be null
,ok 106 error should be null
,# teardown
,2016-04-01 23:50:37.909 ThaliTest[2037:5160971] client: found new peer: BC3134AD-A0D1-47B0-885A-5F5313680802:2
,2016-04-01 23:50:39.554 ThaliTest[2037:5160971] client: found new peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:2
,2016-04-01 23:50:39.782 ThaliTest[2037:5161122] jxcore: stopAdvertisingAndListening
2016-04-01 23:50:39.783 ThaliTest[2037:5161122] THEMultipeerManager stopping peer
2016-04-01 23:50:39.783 ThaliTest[2037:5161122] multipeer manager: stop client timer
20,16-04-01 23:50:39.783 ThaliTest[2037:5161122] jxcore: stopAdvertisingAndListening: success
2016-04-01 23:50:39.784 ThaliTest[2037:5161122] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-04-01 23:50:39.785 ThaliTest[2037:5161122] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 107 error should be null
,ok 108 error should be null
,# setup
,# 28. should be able to call #stopAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 57871
2016-04-01 23:50:55.956 ThaliTest[2037:5161122] jxcore: stopAdvertisingAndListening
2016-04-01 23:50:55.957 ThaliTest[2037:5161122] THEMultipeerManager stopping peer
2016-04-01 23:50:55.957 ThaliTest[2037:5161122] jxcore: stopAdvertisingAndListening: success
,ok 109 error should be null
ok 110 error should be null
2016-04-01 23:50:55.960 ThaliTest[2037:5161122] jxcore: stopAdvertisingAndListening
2016-04-01 23:50:55.961 ThaliTest[2037:5161122] THEMultipeerManager stopping peer
2016-04-01 23:50:55.961 ThaliTest[2037:5161122] jxcore: stopAdvertisingAndListening: success
ok 111 error should be null
ok 112 error should be null
# teardown
,2016-04-01 23:50:56.468 ThaliTest[2037:5161122] jxcore: stopAdvertisingAndListening
2016-04-01 23:50:56.469 ThaliTest[2037:5161122] THEMultipeerManager stopping peer
2016-04-01 23:50:56.469 ThaliTest[2037:5161122] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-01 23:50:56.469 ThaliTest[2037:5161122] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 23:50:56.470 ThaliTest[2037,:5161122] jxcore: stopListeningForAdvertisements: success
,ok 113 error should be null
ok 114 error should be null
,# setup
,# 29. #start should fail if called twice in a row
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 57873
,ok 115 first call should succeed
ok 116 first call should succeed
ok 117 specific error should be returned
# teardown
,2016-04-01 23:50:57.023 ThaliTest[2037:5161122] jxcore: stopAdvertisingAndListening
2016-04-01 23:50:57.023 ThaliTest[2037:5161122] THEMultipeerManager stopping peer
2016-04-01 23:50:57.023 ThaliTest[2037:5161122] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-01 23:50:57.023 ThaliTest[2037:5161122] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 23:50:57.025 ThaliTest[2037:5161122] jxcore: stopListeningForAdvertisements: success
ok 118 error should be null
ok 119 error should be null
# setup
,# 30. does not emit duplicate discoveryAdvertisingStateUpdate
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 57875
,2016-04-01 23:50:57.933 ThaliTest[2037:5161122] jxcore: startListeningForAdvertisements
2016-04-01 23:50:57.934 ThaliTest[2037:5161122] multipeer manager: start client restart timer: 0x15ecd0d0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-01 23:50:57.935 ThaliTest[2037:5161122] jxcore: startListeningForAdvertisements: success
,2016-04-01 23:50:57.949 ThaliTest[2037:5161122] jxcore: startUpdateAdvertisingAndListening
2016-04-01 23:50:57.949 ThaliTest[2037:5161122] server: starting 53FC597F-8F79-47DA-ABAE-0C427F412EFF:3
2016-04-01 23:50:57.950 ThaliTest[2037:5161122] THEMultipeerManager initialized peer 53FC597F-8F79-47DA-ABAE-0C427F412EFF:3
2016-04-01 23:50:57.950 ThaliTest[2037:5161122] jxcore: startUpdateAdvertisingAndListening: success
,ok 120 called only once
,ok 121 discovery state matches
,ok 122 advertising state matches
,# teardown
,2016-04-01 23:50:58.097 ThaliTest[2037:5161122] jxcore: stopAdvertisingAndListening
2016-04-01 23:50:58.097 ThaliTest[2037:5161122] THEMultipeerManager stopping peer
2016-04-01 23:50:58.097 ThaliTest[2037:5161122] jxcore: stopAdvertisingAndListening: suc,cess
2016-04-01 23:50:58.097 ThaliTest[2037:5161122] jxcore: stopListeningForAdvertisements
2016-04-01 23:50:58.098 ThaliTest[2037:5161122] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"adv,ertisingActive":false,"discoveryActive":false}
2016-04-01 23:50:58.099 ThaliTest[2037:5161122] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
INFO thaliMobile: Filtered, out discoveryAdvertisingStateUpdate (was in stopped state).
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 123 error should be null
ok 124 error should be null
,# setup
,# 31. does not send duplicate availability changes
,ok 125 should be called once
ok 126 should not have been called more than once
# teardown
,ok 127 error should be null
,ok 128 error should be null
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
ok 135 port should should be null
,# teardown
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 136 error should be null
ok 137 error should be null
,# setup
,# 34. Can call start/stopListeningForAdvertisements
,2016-04-01 23:51:27.757 ThaliTest[2037:5161122] jxcore: startListeningForAdvertisements
2016-04-01 23:51:27.758 ThaliTest[2037:5161122] multipeer manager: start client restart timer: 0x15ecd0d0
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-01 23:51:27.759 ThaliTest[2037:5161122] jxcore: startListeningForAdvertisements: success
,ok 138 Can call startListeningForAdvertisements without error
2016-04-01 23:51:27.761 ThaliTest[2037:5161122] jxcore: stopListeningForAdvertisements
2016-04-01 23:51:27.761 ThaliTest[2037:5161122] multipeer manager: stop client timer
DEBUG thaliMobileNa,tiveWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 23:51:27.762 ThaliTest[2037:5161122] jxcore: stopListeningForAdvertisements: success
ok 139 Can call stopListeningForAdvertisements without, error
# teardown
,2016-04-01 23:51:27.916 ThaliTest[2037:5161122] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 23:51:27.917 ThaliTest[2037:51611,22] jxcore: stopListeningForAdvertisements: success
ok 140 Should be able to call stopListeningForAdvertisements in teardown
2016-04-01 23:51:27.918 ThaliTest[2037:5161122] jxcore: stopAdvertisingAndListening
2016-04-01 23:51:27.919 ThaliTest[2037:51611,22] THEMultipeerManager stopping peer
2016-04-01 23:51:27.919 ThaliTest[2037:5161122] jxcore: stopAdvertisingAndListening: success
ok 141 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 35. Calling startListeningForAdvertisements twice is NOT an error
,2016-04-01 23:51:28.552 ThaliTest[2037:5161122] jxcore: startListeningForAdvertisements
2016-04-01 23:51:28.552 ThaliTest[2037:5161122] multipeer manager: start client restart timer: 0x15ecd0d0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpd,ateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-01 23:51:28.554 ThaliTest[2037:5161122] jxcore: startListeningForAdvertisements: success
ok 142 Can call startListeningForAdvertisements without error
2016-04-01 23:51:28.555 ThaliTes,t[2037:5161122] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-04-01 23:51:28.556 ThaliTest[2037:5161122] jxcore: startListeningForAdv,ertisements: success
ok 143 Can call startListeningForAdvertisements twice without error
# teardown
,2016-04-01 23:51:28.669 ThaliTest[2037:5161122] jxcore: stopListeningForAdvertisements
2016-04-01 23:51:28.669 ThaliTest[2037:5161122] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisi,ngActive":false,"discoveryActive":false}
2016-04-01 23:51:28.670 ThaliTest[2037:5161122] jxcore: stopListeningForAdvertisements: success
ok 144 Should be able to call stopListeningForAdvertisements in teardown
2016-04-01 23:51:28.671 ThaliTest[2037:5161,122] jxcore: stopAdvertisingAndListening
2016-04-01 23:51:28.671 ThaliTest[2037:5161122] THEMultipeerManager stopping peer
2016-04-01 23:51:28.671 ThaliTest[2037:5161122] jxcore: stopAdvertisingAndListening: success
ok 145 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 36. Calling stopListeningForAdvertisements without calling start is NOT an error
,2016-04-01 23:51:31.933 ThaliTest[2037:5161122] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 23:51:31.934 ThaliTest[2037:51611,22] jxcore: stopListeningForAdvertisements: success
ok 146 Can call stopListeningForAdvertisements without error
2016-04-01 23:51:31.935 ThaliTest[2037:5161122] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingS,tateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 23:51:31.936 ThaliTest[2037:5161122] jxcore: stopListeningForAdvertisements: success
ok 147 Can call stopListeningForAdvertisements without error
# teardown
,2016-04-01 23:51:50.131 ThaliTest[2037:5161122] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 23:51:50.132 ThaliTest[2037:51611,22] jxcore: stopListeningForAdvertisements: success
ok 148 Should be able to call stopListeningForAdvertisements in teardown
2016-04-01 23:51:50.133 ThaliTest[2037:5161122] jxcore: stopAdvertisingAndListening
2016-04-01 23:51:50.133 ThaliTest[2037:51611,22] THEMultipeerManager stopping peer
2016-04-01 23:51:50.133 ThaliTest[2037:5161122] jxcore: stopAdvertisingAndListening: success
ok 149 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 37. Can call start/stopUpdateAdvertisingAndListening
,2016-04-01 23:51:52.379 ThaliTest[2037:5161122] jxcore: startUpdateAdvertisingAndListening
2016-04-01 23:51:52.380 ThaliTest[2037:5161122] server: starting 53FC597F-8F79-47DA-ABAE-0C427F412EFF:4
2016-04-01 23:51:52.380 ThaliTest[2037:5161122] multipeer m,anager: start client restart timer: 0x15ecd0d0
2016-04-01 23:51:52.380 ThaliTest[2037:5161122] THEMultipeerManager initialized peer 53FC597F-8F79-47DA-ABAE-0C427F412EFF:4
2016-04-01 23:51:52.380 ThaliTest[2037:5161122] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 150 Can call startUpdateAdvertisingAndListening without error
2016-04-01 23:51:52.382 ThaliTest[2037:5161122] jxcore: stopAdvertisingAndListening
2016-04-01 23:51:52.382 ThaliTest[2037:5161122] THEMultipeerManager stopping peer
,2016-04-01 23:51:52.382 ThaliTest[2037:5161122] multipeer manager: stop client timer
2016-04-01 23:51:52.388 ThaliTest[2037:5161122] jxcore: stopAdvertisingAndListening: success
ok 151 Can call stopAdvertisingAndListening without error
# teardown
,2016-04-01 23:51:52.464 ThaliTest[2037:5161122] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-01 23:51:52.466 ThaliTest[2037:5161122] jxcore: stopListeningForAdvertisements: success
,ok 152 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-01 23:51:52.468 ThaliTest[2037:5161122] jxcore: stopAdvertisingAndListening
,2016-04-01 23:51:52.468 ThaliTest[2037:5161122] THEMultipeerManager stopping peer
,2016-04-01 23:51:52.469 ThaliTest[2037:5161122] jxcore: stopAdvertisingAndListening: success
,ok 153 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 38. Calling startUpdateAdvertisingAndListening twice is NOT an error
,2016-04-01 23:51:53.230 ThaliTest[2037:5161122] jxcore: startUpdateAdvertisingAndListening
2016-04-01 23:51:53.230 ThaliTest[2037:5161122] server: starting 53FC597F-8F79-47DA-ABAE-0C427F412EFF:5
2016-04-01 23:51:53.231 ThaliTest[2037:5161122] multipeer m,anager: start client restart timer: 0x15ecd0d0
2016-04-01 23:51:53.231 ThaliTest[2037:5161122] THEMultipeerManager initialized peer 53FC597F-8F79-47DA-ABAE-0C427F412EFF:5
2016-04-01 23:51:53.231 ThaliTest[2037:5161122] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 154 Can call startUpdateAdvertisingAndListening without error
2016-04-01 23:51:53.232 ThaliTest[2037:5161122] jxcore: startUpdateAdvertisingAndListening
2016-04-01 23:51:53.232 ThaliTest[2037:5161122] THEMultipeerManager stopping peer
,2016-04-01 23:51:53.233 ThaliTest[2037:5161122] multipeer manager: stop client timer
2016-04-01 23:51:53.238 ThaliTest[2037:5161122] server: starting 53FC597F-8F79-47DA-ABAE-0C427F412EFF:6
2016-04-01 23:51:53.239 ThaliTest[2037:5161122] multipeer manager,: start client restart timer: 0x15ecd0d0
2016-04-01 23:51:53.239 ThaliTest[2037:5161122] THEMultipeerManager initialized peer 53FC597F-8F79-47DA-ABAE-0C427F412EFF:6
,2016-04-01 23:51:53.239 ThaliTest[2037:5161122] jxcore: startUpdateAdvertisingAndListening: success
ok 155 Can call startUpdateAdvertisingAndListening twice without error
# teardown
,2016-04-01 23:51:53.395 ThaliTest[2037:5161122] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-04-01 23:51:53.396 ThaliTest[2037:5161122] jxcore: stopListeningForAdvertisements: success
ok 156 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-01 23:51:53.397 ThaliTest[2037:5161122] jxcore: stopAdvertisingAndListening
2016-04-01 23:51:53.398 ThaliTest[2037:5161122] THEMultipeerManager stopping peer
2016-04-01 23:51:53.398 ThaliTest[2037:5161122] multipeer manager: stop client timer
,2016-04-01 23:51:53.398 ThaliTest[2037:5161122] jxcore: stopAdvertisingAndListening: success
,ok 157 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 39. Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,2016-04-01 23:51:54.254 ThaliTest[2037:5161122] jxcore: stopAdvertisingAndListening
2016-04-01 23:51:54.254 ThaliTest[2037:5161122] THEMultipeerManager stopping peer
2016-04-01 23:51:54.254 ThaliTest[2037:5161122] jxcore: stopAdvertisingAndListening: suc,cess
ok 158 Can call startUpdateAdvertisingAndListening without error
2016-04-01 23:51:54.256 ThaliTest[2037:5161122] jxcore: stopAdvertisingAndListening
2016-04-01 23:51:54.256 ThaliTest[2037:5161122] THEMultipeerManager stopping peer
2016-04-01 23:51,:54.256 ThaliTest[2037:5161122] jxcore: stopAdvertisingAndListening: success
ok 159 Can call stopAdvertisingAndListening without error
# teardown
,2016-04-01 23:51:56.353 ThaliTest[2037:5161122] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 23:51:56.354 ThaliTest[2037:51611,22] jxcore: stopListeningForAdvertisements: success
ok 160 Should be able to call stopListeningForAdvertisements in teardown
2016-04-01 23:51:56.355 ThaliTest[2037:5161122] jxcore: stopAdvertisingAndListening
2016-04-01 23:51:56.355 ThaliTest[2037:51611,22] THEMultipeerManager stopping peer
2016-04-01 23:51:56.355 ThaliTest[2037:5161122] jxcore: stopAdvertisingAndListening: success
ok 161 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 40. cannot call connect when start listening for advertisements is not active
,2016-04-01 23:51:56.843 ThaliTest[2037:5161122] jxcore: connect foo
2016-04-01 23:51:56.844 ThaliTest[2037:5161122] jxcore: connect: fail: Start browsing first
not ok 162 got right error
  ---
    operator: equal
    expected: 'startListeningForAdvertisements is not active'
    actual:   'Start browsing first'
  ...
,# teardown
,2016-04-01 23:51:56.981 ThaliTest[2037:5161122] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 23:51:56.982 ThaliTest[2037:51611,22] jxcore: stopListeningForAdvertisements: success
ok 163 Should be able to call stopListeningForAdvertisements in teardown
2016-04-01 23:51:56.983 ThaliTest[2037:5161122] jxcore: stopAdvertisingAndListening
2016-04-01 23:51:56.983 ThaliTest[2037:51611,22] THEMultipeerManager stopping peer
2016-04-01 23:51:56.983 ThaliTest[2037:5161122] jxcore: stopAdvertisingAndListening: success
ok 164 Should be able to call stopAdvertisingAndListening in teardown
# setup
,# 41. peerAvailabilityChange is called
,2016-04-01 23:51:58.035 ThaliTest[2037:5161122] jxcore: startUpdateAdvertisingAndListening
2016-04-01 23:51:58.035 ThaliTest[2037:5161122] server: starting 53FC597F-8F79-47DA-ABAE-0C427F412EFF:7
2016-04-01 23:51:58.035 ThaliTest[2037:5161122] multipeer m,anager: start client restart timer: 0x15ecd0d0
2016-04-01 23:51:58.036 ThaliTest[2037:5161122] THEMultipeerManager initialized peer 53FC597F-8F79-47DA-ABAE-0C427F412EFF:7
2016-04-01 23:51:58.036 ThaliTest[2037:5161122] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 165 Can call startUpdateAdvertisingAndListeningwithout error
2016-04-01 23:51:58.037 ThaliTest[2037:5161122] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertising,Active":true,"discoveryActive":true}
2016-04-01 23:51:58.038 ThaliTest[2037:5161122] jxcore: startListeningForAdvertisements: success
ok 166 Can call startListeningForAdvertisements without error
,2016-04-01 23:52:00.036 ThaliTest[2037:5160971] client: found new peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:7
2016-04-01 23:52:00.038 ThaliTest[2037:5160971] client: found new peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:7
ok 167 peers must be an array
o,k 168 peers must not be zero-length
ok 169 peer must have peerIdentifier
ok 170 peerIdentifier must be a string
ok 171 peer must have peerAvailable
ok 172 peer must have pleaseConnect
2016-04-01 23:52:00.038 ThaliTest[2037:5160971] client: found new peer: BC3134AD-A0D1-47B0-885A-5F5313680802:7
# teardown
,2016-04-01 23:52:05.111 ThaliTest[2037:5161122] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-04-01 23:52:05.112 ThaliTest[2037:5161122] jxcore: stopListeningForAdvertisements: success
,ok 173 Should be able to call stopListeningForAdvertisements in teardown
,2016-04-01 23:52:05.113 ThaliTest[2037:5161122] jxcore: stopAdvertisingAndListening
,2016-04-01 23:52:05.114 ThaliTest[2037:5161122] THEMultipeerManager stopping peer
2016-04-01 23:52:05.114 ThaliTest[2037:5161122] multipeer manager: stop client timer
2016-04-01 23:52:05.115 ThaliTest[2037:5161122] jxcore: stopAdvertisingAndListening: success
ok 174 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# 42. Can connect to a remote peer
,2016-04-01 23:52:24.312 ThaliTest[2037:5161122] jxcore: startUpdateAdvertisingAndListening
2016-04-01 23:52:24.312 ThaliTest[2037:5161122] server: starting 53FC597F-8F79-47DA-ABAE-0C427F412EFF:8
2016-04-01 23:52:24.313 ThaliTest[2037:5161122] multipeer m,anager: start client restart timer: 0x15ecd0d0
2016-04-01 23:52:24.313 ThaliTest[2037:5161122] THEMultipeerManager initialized peer 53FC597F-8F79-47DA-ABAE-0C427F412EFF:8
2016-04-01 23:52:24.313 ThaliTest[2037:5161122] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 175 Can call startUpdateAdvertisingAndListening without error
2016-04-01 23:52:24.314 ThaliTest[2037:5161122] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisin,gActive":true,"discoveryActive":true}
2016-04-01 23:52:24.315 ThaliTest[2037:5161122] jxcore: startListeningForAdvertisements: success
ok 176 Can call startListeningForAdvertisements without error
,2016-04-01 23:52:25.270 ThaliTest[2037:5160971] client: found new peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"0B8B74BF-D366-4FF8-B07A-13C8262BA,05D:8","pleaseConnect":0}]
2016-04-01 23:52:25.273 ThaliTest[2037:5161122] jxcore: connect 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8
2016-04-01 23:52:25.273 ThaliTest[2037:5161122] client session: connect
2016-04-01 23:52:25.273 ThaliTest[2037:5161122] cli,ent session: stateChange:0->1 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8
,2016-04-01 23:52:25.279 ThaliTest[2037:5160971] client: found new peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:8
,INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"EEA4391C-4C5F-40D5-B71D-C147ED7B0517:8","pleaseConnect":0}]
,2016-04-01 23:52:26.531 ThaliTest[2037:5160971] multipeer session: reset timer
2016-04-01 23:52:26.531 ThaliTest[2037:5160971] server: rejecting invitation from 0B8B74BF-D366-4FF8-B07A-13C8262BA05D due to previous generation (53FC597F-8F79-47DA-ABAE-0C427,F412EFF:8 != 53FC597F-8F79-47DA-ABAE-0C427F412EFF:7)
,2016-04-01 23:52:26.533 ThaliTest[2037:5160971] multipeer session: reset timer
2016-04-01 23:52:26.533 ThaliTest[2037:5160971] server: rejecting invitation from EEA4391C-4C5F-40D5-B71D-C147ED7B0517 due to previous generation (53FC597F-8F79-47DA-ABAE-0C427F412EFF:8 != 53FC597F-8F79-47DA-ABAE-0C427F412EFF:7)
,2016-04-01 23:52:26.926 ThaliTest[2037:5160971] client: found new peer: BC3134AD-A0D1-47B0-885A-5F5313680802:8
INFO testThaliMobileNative: Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"BC3134AD-A0D1-47B0-885A-5F5313680802:8","pleaseConnect":0}]
,2016-04-01 23:52:29.342 ThaliTest[2037:5161778] client session: p2p link connected
,2016-04-01 23:52:29.379 ThaliTest[2037:5161799] client session: stateChange:1->2 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8
2016-04-01 23:52:29.380 ThaliTest[2037:5161799] client session: fireConnectCallback: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D
2016-04-01 23:52:29.380 ThaliTest[2037:5161799] jxcore: connect: success
,INFO testThaliMobileNative: 
,ok 177 Must have listeningPort
,ok 178 listeningPort must be a number
,ok 179 Connection must have clientPort
,ok 180 clientPort must be a number
,ok 181 Connection must have serverPort
,ok 182 serverPort must be a number
,ok 183 forward connection must have clientPort == 0
,ok 184 forward connection must have serverPort == 0
,# teardown
,2016-04-01 23:52:29.864 ThaliTest[2037:5160971] multipeer session: reset timer
2016-04-01 23:52:29.865 ThaliTest[2037:5160971] server: disconnecting to refresh session (EEA4391C-4C5F-40D5-B71D-C147ED7B0517)
2016-04-01 23:52:29.865 ThaliTest[2037:5160971], server: rejecting invitation from EEA4391C-4C5F-40D5-B71D-C147ED7B0517 due to previous generation (53FC597F-8F79-47DA-ABAE-0C427F412EFF:8 != 53FC597F-8F79-47DA-ABAE-0C427F412EFF:7)
,2016-04-01 23:52:33.187 ThaliTest[2037:5160971] multipeer session: reset timer
2016-04-01 23:52:33.187 ThaliTest[2037:5160971] server: disconnecting to refresh session (EEA4391C-4C5F-40D5-B71D-C147ED7B0517)
2016-04-01 23:52:33.188 ThaliTest[2037:5160971], server: rejecting invitation from EEA4391C-4C5F-40D5-B71D-C147ED7B0517 due to previous generation (53FC597F-8F79-47DA-ABAE-0C427F412EFF:8 != 53FC597F-8F79-47DA-ABAE-0C427F412EFF:7)
,2016-04-01 23:52:36.334 ThaliTest[2037:5160971] multipeer session: reset timer
2016-04-01 23:52:36.335 ThaliTest[2037:5160971] server: disconnecting to refresh session (EEA4391C-4C5F-40D5-B71D-C147ED7B0517)
2016-04-01 23:52:36.335 ThaliTest[2037:5160971], server: rejecting invitation from EEA4391C-4C5F-40D5-B71D-C147ED7B0517 due to previous generation (53FC597F-8F79-47DA-ABAE-0C427F412EFF:8 != 53FC597F-8F79-47DA-ABAE-0C427F412EFF:7)
,2016-04-01 23:52:39.442 ThaliTest[2037:5160971] multipeer session: reset timer
2016-04-01 23:52:39.442 ThaliTest[2037:5160971] server: disconnecting to refresh session (EEA4391C-4C5F-40D5-B71D-C147ED7B0517)
2016-04-01 23:52:39.442 ThaliTest[2037:5160971], server: rejecting invitation from EEA4391C-4C5F-40D5-B71D-C147ED7B0517 due to previous generation (53FC597F-8F79-47DA-ABAE-0C427F412EFF:8 != 53FC597F-8F79-47DA-ABAE-0C427F412EFF:7)
,2016-04-01 23:52:42.608 ThaliTest[2037:5160971] multipeer session: reset timer
2016-04-01 23:52:42.608 ThaliTest[2037:5160971] server: disconnecting to refresh session (EEA4391C-4C5F-40D5-B71D-C147ED7B0517)
2016-04-01 23:52:42.608 ThaliTest[2037:5160971], server: rejecting invitation from EEA4391C-4C5F-40D5-B71D-C147ED7B0517 due to previous generation (53FC597F-8F79-47DA-ABAE-0C427F412EFF:8 != 53FC597F-8F79-47DA-ABAE-0C427F412EFF:7)
,2016-04-01 23:52:44.314 ThaliTest[2037:5160971] multipeer manager: restart client
,2016-04-01 23:52:44.344 ThaliTest[2037:5160971] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8
2016-04-01 23:52:44.345 ThaliTest[2037:5160971] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:8
2016-04-01 23:52:44.346 ThaliTest[2037:5160971] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:8
,2016-04-01 23:52:45.784 ThaliTest[2037:5160971] multipeer session: reset timer
2016-04-01 23:52:45.786 ThaliTest[2037:5160971] server: disconnecting to refresh session (EEA4391C-4C5F-40D5-B71D-C147ED7B0517)
2016-04-01 23:52:45.786 ThaliTest[2037:5160971], server: rejecting invitation from EEA4391C-4C5F-40D5-B71D-C147ED7B0517 due to previous generation (53FC597F-8F79-47DA-ABAE-0C427F412EFF:8 != 53FC597F-8F79-47DA-ABAE-0C427F412EFF:7)
,2016-04-01 23:52:48.996 ThaliTest[2037:5160971] multipeer session: reset timer
2016-04-01 23:52:48.996 ThaliTest[2037:5160971] server: disconnecting to refresh session (EEA4391C-4C5F-40D5-B71D-C147ED7B0517)
,2016-04-01 23:52:48.997 ThaliTest[2037:5160971] server: rejecting invitation from EEA4391C-4C5F-40D5-B71D-C147ED7B0517 due to previous generation (53FC597F-8F79-47DA-ABAE-0C427F412EFF:8 != 53FC597F-8F79-47DA-ABAE-0C427F412EFF:7)
,2016-04-01 23:52:52.140 ThaliTest[2037:5160971] multipeer session: reset timer
2016-04-01 23:52:52.141 ThaliTest[2037:5160971] server: disconnecting to refresh session (EEA4391C-4C5F-40D5-B71D-C147ED7B0517)
2016-04-01 23:52:52.141 ThaliTest[2037:5160971], server: rejecting invitation from EEA4391C-4C5F-40D5-B71D-C147ED7B0517 due to previous generation (53FC597F-8F79-47DA-ABAE-0C427F412EFF:8 != 53FC597F-8F79-47DA-ABAE-0C427F412EFF:7)
,2016-04-01 23:52:55.612 ThaliTest[2037:5160971] multipeer session: reset timer
,2016-04-01 23:52:55.612 ThaliTest[2037:5160971] server: disconnecting to refresh session (EEA4391C-4C5F-40D5-B71D-C147ED7B0517)
2016-04-01 23:52:55.612 ThaliTest[2037:5160971] server: rejecting invitation from EEA4391C-4C5F-40D5-B71D-C147ED7B0517 due to previous generation (53FC597F-8F79-47DA-ABAE-0C427F412EFF:8 != 53FC597F-8F79-47DA-ABAE-0C427F412EFF:7)
,2016-04-01 23:53:04.314 ThaliTest[2037:5160971] multipeer manager: restart client
,2016-04-01 23:53:04.349 ThaliTest[2037:5160971] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:8
2016-04-01 23:53:04.349 ThaliTest[2037:5160971] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:8
2016-04-01 23:53:04.35,1 ThaliTest[2037:5160971] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8
,2016-04-01 23:53:24.314 ThaliTest[2037:5160971] multipeer manager: restart client
,2016-04-01 23:53:24.336 ThaliTest[2037:5160971] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:8
,2016-04-01 23:53:24.352 ThaliTest[2037:5160971] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:8
2016-04-01 23:53:24.353 ThaliTest[2037:5160971] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8
,2016-04-01 23:53:34.344 ThaliTest[2037:5161122] jxcore: stopListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
2016-04-01 23:53:34.345 ThaliTest[2037:516112,2] jxcore: stopListeningForAdvertisements: success
ok 185 Should be able to call stopListeningForAdvertisements in teardown
2016-04-01 23:53:34.346 ThaliTest[2037:5161122] jxcore: stopAdvertisingAndListening
2016-04-01 23:53:34.347 ThaliTest[2037:516112,2] THEMultipeerManager stopping peer
2016-04-01 23:53:34.347 ThaliTest[2037:5161122] client session: disconnect
2016-04-01 23:53:34.347 ThaliTest[2037:5161122] client session: stateChange:2->0 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8
,2016-04-01 23:53:34.358 ThaliTest[2037:5161122] multipeer manager: stop client timer
2016-04-01 23:53:34.358 ThaliTest[2037:5161122] jxcore: stopAdvertisingAndListening: success
ok 186 Should be able to call stopAdvertisingAndListening in teardown
# set,up
,# 43. Get error when trying to double connect to a peer
,2016-04-01 23:53:34.954 ThaliTest[2037:5161122] jxcore: startUpdateAdvertisingAndListening
2016-04-01 23:53:34.954 ThaliTest[2037:5161122] server: starting 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-01 23:53:34.955 ThaliTest[2037:5161122] multipeer m,anager: start client restart timer: 0x15ecd0d0
2016-04-01 23:53:34.955 ThaliTest[2037:5161122] THEMultipeerManager initialized peer 53FC597F-8F79-47DA-ABAE-0C427F412EFF:9
2016-04-01 23:53:34.955 ThaliTest[2037:5161122] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 187 Can call startUpdateAdvertisingAndListening without error
2016-04-01 23:53:34.956 ThaliTest[2037:5161122] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisin,gActive":true,"discoveryActive":true}
2016-04-01 23:53:34.958 ThaliTest[2037:5161122] jxcore: startListeningForAdvertisements: success
ok 188 Can call startListeningForAdvertisements without error
,2016-04-01 23:53:35.636 ThaliTest[2037:5160971] client: found new peer: BC3134AD-A0D1-47B0-885A-5F5313680802:8
,2016-04-01 23:53:35.638 ThaliTest[2037:5160971] client: found new peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:8
2016-04-01 23:53:35.639 ThaliTest[2037:5160971] client: found new peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:8
,2016-04-01 23:53:35.639 ThaliTest[2037:5161122] jxcore: connect BC3134AD-A0D1-47B0-885A-5F5313680802:8
2016-04-01 23:53:35.643 ThaliTest[2037:5161122] client: server will connect
2016-04-01 23:53:35.643 ThaliTest[2037:5161122] client session: reverseConnect
2016-04-01 23:53:35.643 ThaliTest[2037:5161122] client session: stateChange:0->1 BC3134AD-A0D1-47B0-885A-5F5313680802:8
,2016-04-01 23:53:36.113 ThaliTest[2037:5160971] multipeer session: reset timer
2016-04-01 23:53:36.114 ThaliTest[2037:5160971] server: rejecting invitation from 0B8B74BF-D366-4FF8-B07A-13C8262BA05D due to previous generation (53FC597F-8F79-47DA-ABAE-0C427F412EFF:9 != 53FC597F-8F79-47DA-ABAE-0C427F412EFF:8)
,2016-04-01 23:53:37.482 ThaliTest[2037:5161957] client session: not connected BC3134AD-A0D1-47B0-885A-5F5313680802:8
2016-04-01 23:53:37.482 ThaliTest[2037:5161957] client session: onLinkFailure: BC3134AD-A0D1-47B0-885A-5F5313680802
2016-04-01 23:53:37.482 ThaliTest[2037:5161957] client session: disconnect
2016-04-01 23:53:37.482 ThaliTest[2037:5161957] client session: stateChange:1->0 BC3134AD-A0D1-47B0-885A-5F5313680802:8
,2016-04-01 23:53:37.484 ThaliTest[2037:5161957] client session: no connect callback (server initiated)
,2016-04-01 23:53:45.644 ThaliTest[2037:5160971] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative: Scheduling a connect retry - retries left: 9
,2016-04-01 23:53:48.652 ThaliTest[2037:5161122] jxcore: connect BC3134AD-A0D1-47B0-885A-5F5313680802:8
2016-04-01 23:53:48.652 ThaliTest[2037:5161122] client: server will connect
2016-04-01 23:53:48.653 ThaliTest[2037:5161122] client session: reverseConnect
,2016-04-01 23:53:48.653 ThaliTest[2037:5161122] client session: stateChange:0->1 BC3134AD-A0D1-47B0-885A-5F5313680802:8
,2016-04-01 23:53:48.751 ThaliTest[2037:5160971] multipeer session: reset timer
,2016-04-01 23:53:48.751 ThaliTest[2037:5160971] server: disconnecting to refresh session (0B8B74BF-D366-4FF8-B07A-13C8262BA05D)
,2016-04-01 23:53:48.751 ThaliTest[2037:5160971] server: rejecting invitation from 0B8B74BF-D366-4FF8-B07A-13C8262BA05D due to previous generation (53FC597F-8F79-47DA-ABAE-0C427F412EFF:9 != 53FC597F-8F79-47DA-ABAE-0C427F412EFF:8)
,2016-04-01 23:53:48.829 ThaliTest[2037:5162001] client session: not connected BC3134AD-A0D1-47B0-885A-5F5313680802:8
2016-04-01 23:53:48.830 ThaliTest[2037:5162001] client session: onLinkFailure: BC3134AD-A0D1-47B0-885A-5F5313680802
,2016-04-01 23:53:48.830 ThaliTest[2037:5162001] client session: disconnect
,2016-04-01 23:53:48.831 ThaliTest[2037:5162001] client session: stateChange:1->0 BC3134AD-A0D1-47B0-885A-5F5313680802:8
,2016-04-01 23:53:48.832 ThaliTest[2037:5162001] client session: no connect callback (server initiated)
,2016-04-01 23:53:54.956 ThaliTest[2037:5160971] multipeer manager: restart client
,2016-04-01 23:53:54.978 ThaliTest[2037:5160971] client: found updated peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
,2016-04-01 23:53:54.995 ThaliTest[2037:5160971] client: found updated peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
2016-04-01 23:53:54.997 ThaliTest[2037:5160971] client: found updated peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
,2016-04-01 23:53:58.654 ThaliTest[2037:5160971] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 8
,2016-04-01 23:54:01.660 ThaliTest[2037:5161122] jxcore: connect BC3134AD-A0D1-47B0-885A-5F5313680802:8
2016-04-01 23:54:01.660 ThaliTest[2037:5161122] client: server will connect
2016-04-01 23:54:01.660 ThaliTest[2037:5161122] client session: reverseConnect
2016-04-01 23:54:01.660 ThaliTest[2037:5161122] client session: stateChange:0->1 BC3134AD-A0D1-47B0-885A-5F5313680802:9
,2016-04-01 23:54:01.836 ThaliTest[2037:5162026] client session: not connected BC3134AD-A0D1-47B0-885A-5F5313680802:9
,2016-04-01 23:54:01.836 ThaliTest[2037:5162026] client session: onLinkFailure: BC3134AD-A0D1-47B0-885A-5F5313680802
2016-04-01 23:54:01.838 ThaliTest[2037:5162026] client session: disconnect
2016-04-01 23:54:01.838 ThaliTest[2037:5162026] client session:, stateChange:1->0 BC3134AD-A0D1-47B0-885A-5F5313680802:9
2016-04-01 23:54:01.838 ThaliTest[2037:5162026] client session: no connect callback (server initiated)
,2016-04-01 23:54:01.885 ThaliTest[2037:5160971] multipeer session: reset timer
2016-04-01 23:54:01.886 ThaliTest[2037:5160971] server: disconnecting to refresh session (0B8B74BF-D366-4FF8-B07A-13C8262BA05D)
2016-04-01 23:54:01.886 ThaliTest[2037:5160971], server: rejecting invitation from 0B8B74BF-D366-4FF8-B07A-13C8262BA05D due to previous generation (53FC597F-8F79-47DA-ABAE-0C427F412EFF:9 != 53FC597F-8F79-47DA-ABAE-0C427F412EFF:8)
,2016-04-01 23:54:03.550 ThaliTest[2037:5160971] client: lost peer: BC3134AD-A0D1-47B0-885A-5F5313680802
2016-04-01 23:54:03.551 ThaliTest[2037:5160971] client session: onPeerLost: BC3134AD-A0D1-47B0-885A-5F5313680802
2016-04-01 23:54:03.552 ThaliTest[203,7:5160971] client: lost peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D
2016-04-01 23:54:03.552 ThaliTest[2037:5160971] client session: onPeerLost: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D
,2016-04-01 23:54:07.895 ThaliTest[2037:5160971] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
,2016-04-01 23:54:11.661 ThaliTest[2037:5160971] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 7
,2016-04-01 23:54:14.672 ThaliTest[2037:5161122] jxcore: connect BC3134AD-A0D1-47B0-885A-5F5313680802:8
2016-04-01 23:54:14.672 ThaliTest[2037:5161122] client: server will connect
2016-04-01 23:54:14.672 ThaliTest[2037:5161122] client session: reverseConnect
2016-04-01 23:54:14.672 ThaliTest[2037:5161122] client session: stateChange:0->1 BC3134AD-A0D1-47B0-885A-5F5313680802:9
,2016-04-01 23:54:14.956 ThaliTest[2037:5160971] multipeer manager: restart client
,2016-04-01 23:54:14.975 ThaliTest[2037:5160971] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-01 23:54:14.975 ThaliTest[2037:5160971] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
,2016-04-01 23:54:14.983 ThaliTest[2037:5160971] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
,2016-04-01 23:54:15.233 ThaliTest[2037:5160971] multipeer session: reset timer
2016-04-01 23:54:15.233 ThaliTest[2037:5160971] server: disconnecting to refresh session (0B8B74BF-D366-4FF8-B07A-13C8262BA05D)
2016-04-01 23:54:15.233 ThaliTest[2037:5160971], server: rejecting invitation from 0B8B74BF-D366-4FF8-B07A-13C8262BA05D due to previous generation (53FC597F-8F79-47DA-ABAE-0C427F412EFF:9 != 53FC597F-8F79-47DA-ABAE-0C427F412EFF:8)
,2016-04-01 23:54:24.673 ThaliTest[2037:5160971] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative: Connect returned an error: Timed out awaiting reverse connection
INFO testThaliMobileNative: Scheduling a connect ret,ry - retries left: 6
,2016-04-01 23:54:27.620 ThaliTest[2037:5160971] multipeer session: reset timer
2016-04-01 23:54:27.620 ThaliTest[2037:5160971] server: disconnecting to refresh session (0B8B74BF-D366-4FF8-B07A-13C8262BA05D)
2016-04-01 23:54:27.620 ThaliTest[2037:5160971], server: rejecting invitation from 0B8B74BF-D366-4FF8-B07A-13C8262BA05D due to previous generation (53FC597F-8F79-47DA-ABAE-0C427F412EFF:9 != 53FC597F-8F79-47DA-ABAE-0C427F412EFF:8)
,2016-04-01 23:54:27.678 ThaliTest[2037:5161122] jxcore: connect BC3134AD-A0D1-47B0-885A-5F5313680802:8
2016-04-01 23:54:27.679 ThaliTest[2037:5161122] client: already connect(ing/ed) to BC3134AD-A0D1-47B0-885A-5F5313680802:8
2016-04-01 23:54:27.679 Thali,Test[2037:5161122] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 5
,2016-04-01 23:54:30.687 ThaliTest[2037:5161122] jxcore: connect BC3134AD-A0D1-47B0-885A-5F5313680802:8
2016-04-01 23:54:30.688 ThaliTest[2037:5161122] client: already connect(ing/ed) to BC3134AD-A0D1-47B0-885A-5F5313680802:8
2016-04-01 23:54:30.688 Thali,Test[2037:5161122] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 4
,2016-04-01 23:54:33.692 ThaliTest[2037:5161122] jxcore: connect BC3134AD-A0D1-47B0-885A-5F5313680802:8
2016-04-01 23:54:33.693 ThaliTest[2037:5161122] client: already connect(ing/ed) to BC3134AD-A0D1-47B0-885A-5F5313680802:8
2016-04-01 23:54:33.693 ThaliTest[2037:5161122] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 3
,2016-04-01 23:54:34.956 ThaliTest[2037:5160971] multipeer manager: restart client
,2016-04-01 23:54:34.988 ThaliTest[2037:5160971] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
2016-04-01 23:54:34.988 ThaliTest[2037:5160971] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-01 23:54:34.98,9 ThaliTest[2037:5160971] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
,2016-04-01 23:54:36.696 ThaliTest[2037:5161122] jxcore: connect BC3134AD-A0D1-47B0-885A-5F5313680802:8
2016-04-01 23:54:36.696 ThaliTest[2037:5161122] client: already connect(ing/ed) to BC3134AD-A0D1-47B0-885A-5F5313680802:8
2016-04-01 23:54:36.696 Thali,Test[2037:5161122] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 2
,2016-04-01 23:54:39.711 ThaliTest[2037:5161122] jxcore: connect BC3134AD-A0D1-47B0-885A-5F5313680802:8
2016-04-01 23:54:39.711 ThaliTest[2037:5161122] client: already connect(ing/ed) to BC3134AD-A0D1-47B0-885A-5F5313680802:8
2016-04-01 23:54:39.712 Thali,Test[2037:5161122] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
INFO testThaliMobileNative: Scheduling a connect retry - retries left: 1
,2016-04-01 23:54:41.188 ThaliTest[2037:5160971] multipeer session: reset timer
2016-04-01 23:54:41.188 ThaliTest[2037:5160971] server: disconnecting to refresh session (0B8B74BF-D366-4FF8-B07A-13C8262BA05D)
2016-04-01 23:54:41.188 ThaliTest[2037:5160971], server: rejecting invitation from 0B8B74BF-D366-4FF8-B07A-13C8262BA05D due to previous generation (53FC597F-8F79-47DA-ABAE-0C427F412EFF:9 != 53FC597F-8F79-47DA-ABAE-0C427F412EFF:8)
,2016-04-01 23:54:42.717 ThaliTest[2037:5161122] jxcore: connect BC3134AD-A0D1-47B0-885A-5F5313680802:8
2016-04-01 23:54:42.717 ThaliTest[2037:5161122] client: already connect(ing/ed) to BC3134AD-A0D1-47B0-885A-5F5313680802:8
2016-04-01 23:54:42.717 Thali,Test[2037:5161122] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative: Connect returned an error: Already connect(ing/ed)
WARN testThaliMobileNative: Too many connect retries!
,2016-04-01 23:54:47.665 ThaliTest[2037:5162105] client session: not connected BC3134AD-A0D1-47B0-885A-5F5313680802:9
2016-04-01 23:54:47.665 ThaliTest[2037:5162105] client session: onLinkFailure: BC3134AD-A0D1-47B0-885A-5F5313680802
2016-04-01 23:54:47.6,65 ThaliTest[2037:5162105] client session: disconnect
2016-04-01 23:54:47.666 ThaliTest[2037:5162105] client session: stateChange:1->0 BC3134AD-A0D1-47B0-885A-5F5313680802:9
,2016-04-01 23:54:47.668 ThaliTest[2037:5162105] client session: no connect callback (server initiated)
,2016-04-01 23:54:53.814 ThaliTest[2037:5160971] multipeer session: reset timer
2016-04-01 23:54:53.814 ThaliTest[2037:5160971] server: disconnecting to refresh session (0B8B74BF-D366-4FF8-B07A-13C8262BA05D)
2016-04-01 23:54:53.814 ThaliTest[2037:5160971] server: rejecting invitation from 0B8B74BF-D366-4FF8-B07A-13C8262BA05D due to previous generation (53FC597F-8F79-47DA-ABAE-0C427F412EFF:9 != 53FC597F-8F79-47DA-ABAE-0C427F412EFF:8)
,2016-04-01 23:54:54.956 ThaliTest[2037:5160971] multipeer manager: restart client
,2016-04-01 23:54:54.984 ThaliTest[2037:5160971] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
,2016-04-01 23:54:54.988 ThaliTest[2037:5160971] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
,2016-04-01 23:54:54.992 ThaliTest[2037:5160971] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
,2016-04-01 23:55:06.852 ThaliTest[2037:5160971] multipeer session: reset timer
2016-04-01 23:55:06.852 ThaliTest[2037:5160971] server: disconnecting to refresh session (0B8B74BF-D366-4FF8-B07A-13C8262BA05D)
2016-04-01 23:55:06.852 ThaliTest[2037:5160971] server: rejecting invitation from 0B8B74BF-D366-4FF8-B07A-13C8262BA05D due to previous generation (53FC597F-8F79-47DA-ABAE-0C427F412EFF:9 != 53FC597F-8F79-47DA-ABAE-0C427F412EFF:8)
,2016-04-01 23:55:14.956 ThaliTest[2037:5160971] multipeer manager: restart client
,2016-04-01 23:55:14.990 ThaliTest[2037:5160971] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-01 23:55:14.990 ThaliTest[2037:5160971] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
,2016-04-01 23:55:14.997 ThaliTest[2037:5160971] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
,2016-04-01 23:55:19.925 ThaliTest[2037:5160971] multipeer session: reset timer
2016-04-01 23:55:19.925 ThaliTest[2037:5160971] server: disconnecting to refresh session (0B8B74BF-D366-4FF8-B07A-13C8262BA05D)
2016-04-01 23:55:19.925 ThaliTest[2037:5160971] server: rejecting invitation from 0B8B74BF-D366-4FF8-B07A-13C8262BA05D due to previous generation (53FC597F-8F79-47DA-ABAE-0C427F412EFF:9 != 53FC597F-8F79-47DA-ABAE-0C427F412EFF:8)
,2016-04-01 23:55:33.059 ThaliTest[2037:5160971] multipeer session: reset timer
2016-04-01 23:55:33.060 ThaliTest[2037:5160971] server: disconnecting to refresh session (0B8B74BF-D366-4FF8-B07A-13C8262BA05D)
2016-04-01 23:55:33.060 ThaliTest[2037:5160971], server: rejecting invitation from 0B8B74BF-D366-4FF8-B07A-13C8262BA05D due to previous generation (53FC597F-8F79-47DA-ABAE-0C427F412EFF:9 != 53FC597F-8F79-47DA-ABAE-0C427F412EFF:8)
,2016-04-01 23:55:34.956 ThaliTest[2037:5160971] multipeer manager: restart client
,2016-04-01 23:55:34.982 ThaliTest[2037:5160971] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
2016-04-01 23:55:34.982 ThaliTest[2037:5160971] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-01 23:55:34.98,3 ThaliTest[2037:5160971] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
,2016-04-01 23:55:54.956 ThaliTest[2037:5160971] multipeer manager: restart client
,2016-04-01 23:55:54.990 ThaliTest[2037:5160971] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
2016-04-01 23:55:54.990 ThaliTest[2037:5160971] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
2016-04-01 23:55:54.990 ThaliTest[2037:5160971] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
,2016-04-01 23:56:14.956 ThaliTest[2037:5160971] multipeer manager: restart client
,2016-04-01 23:56:14.990 ThaliTest[2037:5160971] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-01 23:56:14.990 ThaliTest[2037:5160971] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
2016-04-01 23:56:14.990 ThaliTest[2037:5160971] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
,2016-04-01 23:56:34.956 ThaliTest[2037:5160971] multipeer manager: restart client
,2016-04-01 23:56:34.987 ThaliTest[2037:5160971] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-01 23:56:34.988 ThaliTest[2037:5160971] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
,2016-04-01 23:56:35.118 ThaliTest[2037:5160971] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
,2016-04-01 23:56:54.956 ThaliTest[2037:5160971] multipeer manager: restart client
,2016-04-01 23:56:54.987 ThaliTest[2037:5160971] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
2016-04-01 23:56:54.988 ThaliTest[2037:5160971] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
,2016-04-01 23:56:54.996 ThaliTest[2037:5160971] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
,2016-04-01 23:57:14.956 ThaliTest[2037:5160971] multipeer manager: restart client
,2016-04-01 23:57:14.988 ThaliTest[2037:5160971] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
2016-04-01 23:57:14.988 ThaliTest[2037:5160971] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
,2016-04-01 23:57:14.995 ThaliTest[2037:5160971] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
,2016-04-01 23:57:34.956 ThaliTest[2037:5160971] multipeer manager: restart client
,2016-04-01 23:57:34.985 ThaliTest[2037:5160971] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-01 23:57:34.986 ThaliTest[2037:5160971] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
2016-04-01 23:57:34.98,6 ThaliTest[2037:5160971] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
,2016-04-01 23:57:54.956 ThaliTest[2037:5160971] multipeer manager: restart client
,2016-04-01 23:57:54.985 ThaliTest[2037:5160971] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-01 23:57:54.985 ThaliTest[2037:5160971] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
2016-04-01 23:57:54.986 ThaliTest[2037:5160971] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
,2016-04-01 23:58:14.956 ThaliTest[2037:5160971] multipeer manager: restart client
,2016-04-01 23:58:14.991 ThaliTest[2037:5160971] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
,2016-04-01 23:58:14.996 ThaliTest[2037:5160971] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-01 23:58:14.996 ThaliTest[2037:5160971] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
,2016-04-01 23:58:34.956 ThaliTest[2037:5160971] multipeer manager: restart client
,2016-04-01 23:58:34.992 ThaliTest[2037:5160971] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
2016-04-01 23:58:34.993 ThaliTest[2037:5160971] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-01 23:58:34.994 ThaliTest[2037:5160971] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
,2016-04-01 23:58:54.956 ThaliTest[2037:5160971] multipeer manager: restart client
,2016-04-01 23:58:54.989 ThaliTest[2037:5160971] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-01 23:58:54.989 ThaliTest[2037:5160971] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
2016-04-01 23:58:54.992 ThaliTest[2037:5160971] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
,2016-04-01 23:59:14.956 ThaliTest[2037:5160971] multipeer manager: restart client
,2016-04-01 23:59:14.986 ThaliTest[2037:5160971] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-01 23:59:14.987 ThaliTest[2037:5160971] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
2016-04-01 23:59:14.98,7 ThaliTest[2037:5160971] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
,2016-04-01 23:59:34.956 ThaliTest[2037:5160971] multipeer manager: restart client
,2016-04-01 23:59:34.983 ThaliTest[2037:5160971] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
2016-04-01 23:59:34.983 ThaliTest[2037:5160971] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-01 23:59:34.984 ThaliTest[2037:5160971] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
,2016-04-01 23:59:54.956 ThaliTest[2037:5160971] multipeer manager: restart client
,2016-04-01 23:59:54.992 ThaliTest[2037:5160971] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-01 23:59:54.992 ThaliTest[2037:5160971] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
,2016-04-01 23:59:54.998 ThaliTest[2037:5160971] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
,2016-04-02 00:00:14.956 ThaliTest[2037:5160971] multipeer manager: restart client
,2016-04-02 00:00:14.982 ThaliTest[2037:5160971] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
2016-04-02 00:00:14.984 ThaliTest[2037:5160971] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-02 00:00:14.984 ThaliTest[2037:5160971] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
,2016-04-02 00:00:34.956 ThaliTest[2037:5160971] multipeer manager: restart client
,2016-04-02 00:00:34.983 ThaliTest[2037:5160971] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
2016-04-02 00:00:34.983 ThaliTest[2037:5160971] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-02 00:00:34.985 ThaliTest[2037:5160971] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
,2016-04-02 00:00:54.956 ThaliTest[2037:5160971] multipeer manager: restart client
,2016-04-02 00:00:54.995 ThaliTest[2037:5160971] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-02 00:00:54.995 ThaliTest[2037:5160971] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
2016-04-02 00:00:54.996 ThaliTest[2037:5160971] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
,2016-04-02 00:01:14.956 ThaliTest[2037:5160971] multipeer manager: restart client
,2016-04-02 00:01:14.990 ThaliTest[2037:5160971] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
2016-04-02 00:01:14.992 ThaliTest[2037:5160971] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-02 00:01:14.992 ThaliTest[2037:5160971] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
,2016-04-02 00:01:34.956 ThaliTest[2037:5160971] multipeer manager: restart client
,2016-04-02 00:01:34.987 ThaliTest[2037:5160971] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
2016-04-02 00:01:34.988 ThaliTest[2037:5160971] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-02 00:01:34.98,8 ThaliTest[2037:5160971] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
,2016-04-02 00:01:54.956 ThaliTest[2037:5160971] multipeer manager: restart client
,2016-04-02 00:01:54.992 ThaliTest[2037:5160971] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-02 00:01:54.992 ThaliTest[2037:5160971] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
,2016-04-02 00:01:54.998 ThaliTest[2037:5160971] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
,2016-04-02 00:02:14.956 ThaliTest[2037:5160971] multipeer manager: restart client
,2016-04-02 00:02:14.989 ThaliTest[2037:5160971] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
2016-04-02 00:02:14.990 ThaliTest[2037:5160971] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
2016-04-02 00:02:14.990 ThaliTest[2037:5160971] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
,2016-04-02 00:02:34.956 ThaliTest[2037:5160971] multipeer manager: restart client
,2016-04-02 00:02:34.992 ThaliTest[2037:5160971] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-02 00:02:34.993 ThaliTest[2037:5160971] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
2016-04-02 00:02:34.994 ThaliTest[2037:5160971] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
,2016-04-02 00:02:54.955 ThaliTest[2037:5160971] multipeer manager: restart client
,2016-04-02 00:02:54.978 ThaliTest[2037:5160971] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-02 00:02:54.980 ThaliTest[2037:5160971] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
2016-04-02 00:02:54.980 ThaliTest[2037:5160971] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
,2016-04-02 00:03:14.956 ThaliTest[2037:5160971] multipeer manager: restart client
,2016-04-02 00:03:14.992 ThaliTest[2037:5160971] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
2016-04-02 00:03:14.992 ThaliTest[2037:5160971] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-02 00:03:14.99,2 ThaliTest[2037:5160971] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
,2016-04-02 00:03:34.956 ThaliTest[2037:5160971] multipeer manager: restart client
,2016-04-02 00:03:34.991 ThaliTest[2037:5160971] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
,2016-04-02 00:03:34.997 ThaliTest[2037:5160971] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-02 00:03:34.998 ThaliTest[2037:5160971] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
,2016-04-02 00:03:54.956 ThaliTest[2037:5160971] multipeer manager: restart client
,2016-04-02 00:03:54.992 ThaliTest[2037:5160971] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
,2016-04-02 00:03:54.995 ThaliTest[2037:5160971] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
2016-04-02 00:03:54.995 ThaliTest[2037:5160971] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
,2016-04-02 00:04:14.955 ThaliTest[2037:5160971] multipeer manager: restart client
,2016-04-02 00:04:14.990 ThaliTest[2037:5160971] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-02 00:04:14.992 ThaliTest[2037:5160971] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
2016-04-02 00:04:14.992 ThaliTest[2037:5160971] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
,2016-04-02 00:04:34.956 ThaliTest[2037:5160971] multipeer manager: restart client
,2016-04-02 00:04:34.990 ThaliTest[2037:5160971] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-02 00:04:34.991 ThaliTest[2037:5160971] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
2016-04-02 00:04:34.99,2 ThaliTest[2037:5160971] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
,2016-04-02 00:04:54.956 ThaliTest[2037:5160971] multipeer manager: restart client
,2016-04-02 00:04:54.993 ThaliTest[2037:5160971] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-02 00:04:54.994 ThaliTest[2037:5160971] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
2016-04-02 00:04:54.995 ThaliTest[2037:5160971] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
,2016-04-02 00:05:14.956 ThaliTest[2037:5160971] multipeer manager: restart client
,2016-04-02 00:05:14.991 ThaliTest[2037:5160971] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
2016-04-02 00:05:14.991 ThaliTest[2037:5160971] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
,2016-04-02 00:05:14.993 ThaliTest[2037:5160971] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
,2016-04-02 00:05:34.956 ThaliTest[2037:5160971] multipeer manager: restart client
,2016-04-02 00:05:34.981 ThaliTest[2037:5160971] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
2016-04-02 00:05:34.982 ThaliTest[2037:5160971] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-02 00:05:34.984 ThaliTest[2037:5160971] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
,2016-04-02 00:05:54.956 ThaliTest[2037:5160971] multipeer manager: restart client
,2016-04-02 00:05:54.994 ThaliTest[2037:5160971] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
2016-04-02 00:05:54.994 ThaliTest[2037:5160971] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-02 00:05:54.995 ThaliTest[2037:5160971] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
,2016-04-02 00:06:14.956 ThaliTest[2037:5160971] multipeer manager: restart client
,2016-04-02 00:06:14.992 ThaliTest[2037:5160971] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
2016-04-02 00:06:14.992 ThaliTest[2037:5160971] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
,2016-04-02 00:06:14.997 ThaliTest[2037:5160971] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
,2016-04-02 00:06:34.956 ThaliTest[2037:5160971] multipeer manager: restart client
,2016-04-02 00:06:34.991 ThaliTest[2037:5160971] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
2016-04-02 00:06:34.991 ThaliTest[2037:5160971] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
,2016-04-02 00:06:34.996 ThaliTest[2037:5160971] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
,2016-04-02 00:06:54.956 ThaliTest[2037:5160971] multipeer manager: restart client
,2016-04-02 00:06:54.984 ThaliTest[2037:5160971] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-02 00:06:54.985 ThaliTest[2037:5160971] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
2016-04-02 00:06:54.98,5 ThaliTest[2037:5160971] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
,2016-04-02 00:07:14.956 ThaliTest[2037:5160971] multipeer manager: restart client
,2016-04-02 00:07:14.991 ThaliTest[2037:5160971] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
2016-04-02 00:07:14.993 ThaliTest[2037:5160971] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-02 00:07:14.993 ThaliTest[2037:5160971] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
,2016-04-02 00:07:34.956 ThaliTest[2037:5160971] multipeer manager: restart client
,2016-04-02 00:07:34.992 ThaliTest[2037:5160971] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
,2016-04-02 00:07:34.997 ThaliTest[2037:5160971] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-02 00:07:34.998 ThaliTest[2037:5160971] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
,2016-04-02 00:07:54.956 ThaliTest[2037:5160971] multipeer manager: restart client
,2016-04-02 00:07:54.987 ThaliTest[2037:5160971] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
,2016-04-02 00:07:54.989 ThaliTest[2037:5160971] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
2016-04-02 00:07:54.990 ThaliTest[2037:5160971] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
,2016-04-02 00:08:14.956 ThaliTest[2037:5160971] multipeer manager: restart client
,2016-04-02 00:08:14.984 ThaliTest[2037:5160971] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
2016-04-02 00:08:14.985 ThaliTest[2037:5160971] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-02 00:08:14.986 ThaliTest[2037:5160971] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
,2016-04-02 00:08:34.956 ThaliTest[2037:5160971] multipeer manager: restart client
,2016-04-02 00:08:34.988 ThaliTest[2037:5160971] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
2016-04-02 00:08:34.988 ThaliTest[2037:5160971] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-02 00:08:34.98,8 ThaliTest[2037:5160971] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9
,2016-04-02 00:08:54.956 ThaliTest[2037:5160971] multipeer manager: restart client
,2016-04-02 00:08:54.992 ThaliTest[2037:5160971] client: found existing peer: BC3134AD-A0D1-47B0-885A-5F5313680802:9
2016-04-02 00:08:54.995 ThaliTest[2037:5160971] client: found existing peer: 0B8B74BF-D366-4FF8-B07A-13C8262BA05D:9
2016-04-02 00:08:54.995 ThaliTest[2037:5160971] client: found existing peer: EEA4391C-4C5F-40D5-B71D-C147ED7B0517:9

```
