#### Test 648099366fd8e87_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/648099366fd8e87/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/51610474-297B-4B73-876E-E200F173AAB4/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/51610474-297B-4B73-876E-E200F173AAB4/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/648099366fd8e87/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/648099366fd8e87/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/F410C91D-CC62-4DF2-BEBC-CD1EE51ACE35/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50192"
,(lldb)     command script import "/tmp/51610474-297B-4B73-876E-E200F173AAB4/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-04-01 10:26:23.632 ThaliTest[2666:4852557] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/AE5D65BA-4897-4B0D-A35E-69DE139EE1CC/Library/Cookies/Cookies.binarycookies
,2016-04-01 10:26:23.888 ThaliTest[2666:4852557] Apache Cordova native platform version 4.1.0 is starting.
,2016-04-01 10:26:23.889 ThaliTest[2666:4852557] Multi-tasking -> Device: YES, App: YES
,2016-04-01 10:26:23.905 ThaliTest[2666:4852557] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-04-01 10:26:24.716 ThaliTest[2666:4852557] Using UIWebView
,2016-04-01 10:26:24.721 ThaliTest[2666:4852557] [CDVTimer][handleopenurl] 0.177026ms
2016-04-01 10:26:24.723 ThaliTest[2666:4852557] [CDVTimer][intentandnavigationfilter] 2.618015ms
2016-04-01 10:26:24.724 ThaliTest[2666:4852557] [CDVTimer][gesturehandle,r] 0.118971ms
2016-04-01 10:26:24.724 ThaliTest[2666:4852557] [CDVTimer][TotalPluginStartup] 3.548026ms
,2016-04-01 10:26:27.934 ThaliTest[2666:4852557] Resetting plugins due to page load.
,2016-04-01 10:26:29.421 ThaliTest[2666:4852557] Finished load of: file:///var/mobile/Containers/Bundle/Application/F410C91D-CC62-4DF2-BEBC-CD1EE51ACE35/ThaliTest.app/www/index.html
,2016-04-01 10:26:29.599 ThaliTest[2666:4852557] JXcore Cordova plugin initializing
,2016-04-01 10:26:29.601 ThaliTest[2666:4852701] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-04-01 10:26:38.112 ThaliTest[2666:4852701] jxcore: didRegisterToNative peerAvailabilityChanged
2016-04-01 10:26:38.112 ThaliTest[2666:4852701] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-04-01 10:26:38.112 ThaliTest[2666:4,852701] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-04-01 10:26:38.115 ThaliTest[2666:4852701] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5s-1
,WARN testUtils: myNameCallback not set!
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F410C91D-CC62-4DF2-BEBC-CD1EE51ACE35/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F410C91D-CC62-4DF2-BEBC-CD1EE51ACE35/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F410C91D-CC62-4DF2-BEBC-CD1EE51ACE35/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F410C91D-CC62-4DF2-BEBC-CD1EE51ACE35/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F410C91D-CC62-4DF2-BEBC-CD1EE51ACE35/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F410C91D-CC62-4DF2-BEBC-CD1EE51ACE35/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F410C91D-CC62-4DF2-BEBC-CD1EE51ACE35/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F410C91D-CC62-4DF2-BEBC-CD1EE51ACE35/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F410C91D-CC62-4DF2-BEBC-CD1EE51ACE35/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F410C91D-CC62-4DF2-BEBC-CD1EE51ACE35/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F410C91D-CC62-4DF2-BEBC-CD1EE51ACE35/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F410C91D-CC62-4DF2-BEBC-CD1EE51ACE35/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F410C91D-CC62-4DF2-BEBC-CD1EE51ACE35/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F410C91D-CC62-4DF2-BEBC-CD1EE51ACE35/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F410C91D-CC62-4DF2-BEBC-CD1EE51ACE35/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F410C91D-CC62-4DF2-BEBC-CD1EE51ACE35/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F410C91D-CC62-4DF2-BEBC-CD1EE51ACE35/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F410C91D-CC62-4DF2-BEBC-CD1EE51ACE35/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F410C91D-CC62-4DF2-BEBC-CD1EE51ACE35/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F410C91D-CC62-4DF2-BEBC-CD1EE51ACE35/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F410C91D-CC62-4DF2-BEBC-CD1EE51ACE35/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F410C91D-CC62-4DF2-BEBC-CD1EE51ACE35/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 57953
ok 1 Should throw
# teardown
,# setup
,# 2. emits incomingConnectionState
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 57955
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
DEBUG createNativeListener: listening 57958
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
DEBUG createNativeListener: listening 57962
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
# setup
DEBUG createNativeListener: incoming socket close
,# 5. native server - closing incoming stream cleans outgoing socket
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 57967
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
DEBUG createNativeListener: listening 57971
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
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
DEBUG createNativeListener: listening 57975
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
,DEBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: stream close:
,ok 17 stream was closed
,ok 18 incoming should survive
ok 19 mux should have no streams
,# teardown
,DEBUG createNativeListener: mux close
,# setup
DEBUG createNativeListener: incoming socket close
,# 8. native server - closing the whole server cleans everything up
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 57979
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,ok 20 we should not have gotten an error
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
DEBUG createNativeListener: listening 57983
,DEBUG createNativeListener: new incoming socket
,DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createN,ativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new ,mux
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
D,EBUG createNativeListener: new mux
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
DEBUG createNativeListener: new stream: 
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
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
,DEBUG createNativeListener: new outgoing socket
,DEBUG createNativeListener: new stream: 
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
DEBUG createNativeListener: listening 58035
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
ok 33 server should be fine
ok 34 server should be open
ok 35 incoming has been removed
ok 36 The mux object should be closed
ok 37 The mux stream should be closed
,# teardown
,# setup
,# 11. native server - timing out the incoming connection cleans everything up
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 58039
,DEBUG createNativeListener: new incoming socket
DEBUG createNativeListener: creating incoming mux
DEBUG createNativeListener: new mux
,ok 38 we should not have gotten an error
,DEBUG createNativeListener: new stream: 
DEBUG createNativeListener: new outgoing socket
,ok 39 Buffers are identical
,DEBUG createNativeListener: incoming socket timeout
,DEBUG createNativeListener: stream close:
,DEBUG createNativeListener: mux close
,DEBUG createNativeListener: incoming socket close
ok 40 server should be fine
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
,# teardown
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
,[{"uuid":"ccbe122f-8216-4649-a64f-eb913b58c9dd","data":"custom data"},{"uuid":"a43a42fb-60cd-429b-9482-f47c6b29e394","data":"custom data"},{"uuid":"674acf2f-26d0-4b75-8664-1b61e32c9c92","data":"custom data"},{"uuid":"4f3079db-5318-489d-b5a2-5da219f54744",",data":"custom data"}]
ok 76 test participant has uuid
ok 77 participant data matches
ok 78 test participant has uuid
ok 79 participant data matches
ok 80 test participant has uuid
ok 81 participant data matches
ok 82 test participant has uuid
ok 83 participant data matches
,ok 84 own UUID is found from the participants list
,# teardown
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
,DEBUG createNativeListener: listening 58049
,2016-04-01 10:29:11.265 ThaliTest[2666:4852701] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-01 10:29:11.266 ThaliTest[2666:4852701] jxcore: stopListeningForAdvertisements: success
,ok 91 error should be null
ok 92 error should be null
,2016-04-01 10:29:11.269 ThaliTest[2666:4852701] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-01 10:29:11.270 ThaliTest[2666:4852701] jxcore: stopListeningForAdvertisements: success
,ok 93 error should be null
,ok 94 error should be null
,# teardown
,2016-04-01 10:29:11.440 ThaliTest[2666:4852701] jxcore: stopAdvertisingAndListening
,2016-04-01 10:29:11.440 ThaliTest[2666:4852701] THEMultipeerManager stopping peer
,2016-04-01 10:29:11.441 ThaliTest[2666:4852701] jxcore: stopAdvertisingAndListening: success
,2016-04-01 10:29:11.442 ThaliTest[2666:4852701] jxcore: stopListeningForAdvertisements
,DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-04-01 10:29:11.443 ThaliTest[2666:4852701] jxcore: stopListeningForAdvertisements: success
,ok 95 error should be null
,ok 96 error should be null
,# setup
,# 26. should be able to call #startListeningForAdvertisements many times
,DEBUG createNativeListener: creating native server
,DEBUG createNativeListener: listening 58051
,2016-04-01 10:29:11.816 ThaliTest[2666:4852701] jxcore: startListeningForAdvertisements
,2016-04-01 10:29:11.818 ThaliTest[2666:4852701] multipeer manager: start client restart timer: 0x166d5ec0
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-01 10:29:11.821 ThaliTest[2666:4852701] jxcore: startListeningForAdvertisements: success
,ok 97 error should be null
,ok 98 error should be null
,2016-04-01 10:29:11.964 ThaliTest[2666:4852701] jxcore: startListeningForAdvertisements
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-04-01 10:29:11.965 ThaliTest[2666:4852701] jxcore: startListeningForAdvertisements: success
,ok 99 error should be null
,ok 100 error should be null
,# teardown
,2016-04-01 10:29:12.162 ThaliTest[2666:4852701] jxcore: stopAdvertisingAndListening
2016-04-01 10:29:12.163 ThaliTest[2666:4852701] THEMultipeerManager stopping peer
2016-04-01 10:29:12.163 ThaliTest[2666:4852701] jxcore: stopAdvertisingAndListening: success
2016-04-01 10:29:12.163 ThaliTest[2666:4852701] jxcore: stopListeningForAdvertisements
2016-04-01 10:29:12.163 ThaliTest[2666:4852701] multipeer manager: stop client timer
DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
2016-04-01 10:29:12.164 ThaliTest[2666:4852701] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 101 error should be null
ok 102 error should be null
# setup
,# 27. should be able to call #startUpdateAdvertisingAndListening many times
,DEBUG createNativeListener: creating native server
DEBUG createNativeListener: listening 58053
,2016-04-01 10:29:20.762 ThaliTest[2666:4852701] jxcore: startUpdateAdvertisingAndListening
2016-04-01 10:29:20.762 ThaliTest[2666:4852701] server: starting AF7387D0-0090-4A65-A0D9-8EC73F2CF73F:1
2016-04-01 10:29:20.762 ThaliTest[2666:4852701] multipeer manager: start client restart timer: 0x166d5ec0
2016-04-01 10:29:20.762 ThaliTest[2666:4852701] THEMultipeerManager initialized peer AF7387D0-0090-4A65-A0D9-8EC73F2CF73F:1
2016-04-01 10:29:20.762 ThaliTest[2666:4852701] jxcore: startUpdateAdvertisingAndLi,stening: success
,ok 103 error should be null
ok 104 error should be null
2016-04-01 10:29:20.774 ThaliTest[2666:4852701] jxcore: startUpdateAdvertisingAndListening
2016-04-01 10:29:20.774 ThaliTest[2666:4852701] THEMultipeerManager stopping peer
2016-04-01 10:29:20.775 ThaliTest[2666:4852701] multipeer manager: stop client timer
2016-04-01 10:29:20.775 ThaliTest[2666:4852701] server: starting AF7387D0-0090-4A65-A0D9-8EC73F2CF73F:2
2016-04-01 10:29:20.775 ThaliTest[2666:4852701] multipeer manager: start client restart ,timer: 0x166d5ec0
2016-04-01 10:29:20.775 ThaliTest[2666:4852701] THEMultipeerManager initialized peer AF7387D0-0090-4A65-A0D9-8EC73F2CF73F:2
2016-04-01 10:29:20.776 ThaliTest[2666:4852701] jxcore: startUpdateAdvertisingAndListening: success
,2016-04-01 10:29:20.789 ThaliTest[2666:4852557] client: found new peer: 8094618C-E7CE-4DA5-8DA1-5309D649EE33:2
,ok 105 error should be null
ok 106 error should be null
,# teardown
,2016-04-01 10:29:21.926 ThaliTest[2666:4852557] client: found new peer: 4702DF1C-DA47-4E5C-BCD4-B1278D5E4DE6:2
,2016-04-01 10:29:28.229 ThaliTest[2666:4852557] client: lost peer: 4702DF1C-DA47-4E5C-BCD4-B1278D5E4DE6
2016-04-01 10:29:28.229 ThaliTest[2666:4852557] client session: onPeerLost: 4702DF1C-DA47-4E5C-BCD4-B1278D5E4DE6
,2016-04-01 10:29:30.169 ThaliTest[2666:4852557] client: found new peer: 7A3E2FC9-9ECE-4B84-83EC-3B5A7BABEB7A:2
,2016-04-01 10:29:40.776 ThaliTest[2666:4852557] multipeer manager: restart client
,2016-04-01 10:29:40.793 ThaliTest[2666:4852557] client: found existing peer: 8094618C-E7CE-4DA5-8DA1-5309D649EE33:2
,2016-04-01 10:29:40.797 ThaliTest[2666:4852557] client: found existing peer: 7A3E2FC9-9ECE-4B84-83EC-3B5A7BABEB7A:2
,2016-04-01 10:29:50.635 ThaliTest[2666:4852557] client: lost peer: 8094618C-E7CE-4DA5-8DA1-5309D649EE33
2016-04-01 10:29:50.636 ThaliTest[2666:4852557] client session: onPeerLost: 8094618C-E7CE-4DA5-8DA1-5309D649EE33
,2016-04-01 10:30:00.776 ThaliTest[2666:4852557] multipeer manager: restart client
,2016-04-01 10:30:00.797 ThaliTest[2666:4852557] client: found existing peer: 7A3E2FC9-9ECE-4B84-83EC-3B5A7BABEB7A:2
,2016-04-01 10:30:20.776 ThaliTest[2666:4852557] multipeer manager: restart client
,2016-04-01 10:30:20.786 ThaliTest[2666:4852557] client: found existing peer: 7A3E2FC9-9ECE-4B84-83EC-3B5A7BABEB7A:2
,2016-04-01 10:30:40.776 ThaliTest[2666:4852557] multipeer manager: restart client
,2016-04-01 10:30:40.792 ThaliTest[2666:4852557] client: found existing peer: 7A3E2FC9-9ECE-4B84-83EC-3B5A7BABEB7A:2
,2016-04-01 10:30:55.985 ThaliTest[2666:4852557] client: lost peer: 7A3E2FC9-9ECE-4B84-83EC-3B5A7BABEB7A
2016-04-01 10:30:55.985 ThaliTest[2666:4852557] client session: onPeerLost: 7A3E2FC9-9ECE-4B84-83EC-3B5A7BABEB7A
,2016-04-01 10:31:00.776 ThaliTest[2666:4852557] multipeer manager: restart client
,2016-04-01 10:31:00.787 ThaliTest[2666:4852557] client: found existing peer: 7A3E2FC9-9ECE-4B84-83EC-3B5A7BABEB7A:2
,2016-04-01 10:31:20.776 ThaliTest[2666:4852557] multipeer manager: restart client
,2016-04-01 10:31:20.787 ThaliTest[2666:4852557] client: found existing peer: 7A3E2FC9-9ECE-4B84-83EC-3B5A7BABEB7A:2
,2016-04-01 10:31:40.776 ThaliTest[2666:4852557] multipeer manager: restart client
,2016-04-01 10:31:41.509 ThaliTest[2666:4852557] client: found existing peer: 7A3E2FC9-9ECE-4B84-83EC-3B5A7BABEB7A:2
,2016-04-01 10:32:00.776 ThaliTest[2666:4852557] multipeer manager: restart client
,2016-04-01 10:32:00.795 ThaliTest[2666:4852557] client: found existing peer: 7A3E2FC9-9ECE-4B84-83EC-3B5A7BABEB7A:2
,2016-04-01 10:32:20.776 ThaliTest[2666:4852557] multipeer manager: restart client
,2016-04-01 10:32:20.789 ThaliTest[2666:4852557] client: found existing peer: 7A3E2FC9-9ECE-4B84-83EC-3B5A7BABEB7A:2
,2016-04-01 10:32:40.776 ThaliTest[2666:4852557] multipeer manager: restart client
,2016-04-01 10:32:40.787 ThaliTest[2666:4852557] client: found existing peer: 7A3E2FC9-9ECE-4B84-83EC-3B5A7BABEB7A:2
,2016-04-01 10:33:00.776 ThaliTest[2666:4852557] multipeer manager: restart client
,2016-04-01 10:33:00.789 ThaliTest[2666:4852557] client: found existing peer: 7A3E2FC9-9ECE-4B84-83EC-3B5A7BABEB7A:2
,2016-04-01 10:33:20.776 ThaliTest[2666:4852557] multipeer manager: restart client
,2016-04-01 10:33:20.793 ThaliTest[2666:4852557] client: found existing peer: 7A3E2FC9-9ECE-4B84-83EC-3B5A7BABEB7A:2
,2016-04-01 10:33:40.776 ThaliTest[2666:4852557] multipeer manager: restart client
,2016-04-01 10:33:40.790 ThaliTest[2666:4852557] client: found existing peer: 7A3E2FC9-9ECE-4B84-83EC-3B5A7BABEB7A:2
,2016-04-01 10:34:00.776 ThaliTest[2666:4852557] multipeer manager: restart client
,2016-04-01 10:34:00.795 ThaliTest[2666:4852557] client: found existing peer: 7A3E2FC9-9ECE-4B84-83EC-3B5A7BABEB7A:2
,2016-04-01 10:34:20.776 ThaliTest[2666:4852557] multipeer manager: restart client
,2016-04-01 10:34:20.788 ThaliTest[2666:4852557] client: found existing peer: 7A3E2FC9-9ECE-4B84-83EC-3B5A7BABEB7A:2
,2016-04-01 10:34:40.776 ThaliTest[2666:4852557] multipeer manager: restart client
,2016-04-01 10:34:40.788 ThaliTest[2666:4852557] client: found existing peer: 7A3E2FC9-9ECE-4B84-83EC-3B5A7BABEB7A:2
,2016-04-01 10:35:00.776 ThaliTest[2666:4852557] multipeer manager: restart client
,2016-04-01 10:35:00.789 ThaliTest[2666:4852557] client: found existing peer: 7A3E2FC9-9ECE-4B84-83EC-3B5A7BABEB7A:2
,2016-04-01 10:35:20.776 ThaliTest[2666:4852557] multipeer manager: restart client
,2016-04-01 10:35:20.794 ThaliTest[2666:4852557] client: found existing peer: 7A3E2FC9-9ECE-4B84-83EC-3B5A7BABEB7A:2
,2016-04-01 10:35:40.776 ThaliTest[2666:4852557] multipeer manager: restart client
,2016-04-01 10:35:40.789 ThaliTest[2666:4852557] client: found existing peer: 7A3E2FC9-9ECE-4B84-83EC-3B5A7BABEB7A:2
,2016-04-01 10:36:00.776 ThaliTest[2666:4852557] multipeer manager: restart client
,2016-04-01 10:36:00.786 ThaliTest[2666:4852557] client: found existing peer: 7A3E2FC9-9ECE-4B84-83EC-3B5A7BABEB7A:2
,2016-04-01 10:36:20.776 ThaliTest[2666:4852557] multipeer manager: restart client
,2016-04-01 10:36:20.795 ThaliTest[2666:4852557] client: found existing peer: 7A3E2FC9-9ECE-4B84-83EC-3B5A7BABEB7A:2
,2016-04-01 10:36:40.776 ThaliTest[2666:4852557] multipeer manager: restart client
,2016-04-01 10:36:40.789 ThaliTest[2666:4852557] client: found existing peer: 7A3E2FC9-9ECE-4B84-83EC-3B5A7BABEB7A:2
,2016-04-01 10:37:00.776 ThaliTest[2666:4852557] multipeer manager: restart client
,2016-04-01 10:37:00.789 ThaliTest[2666:4852557] client: found existing peer: 7A3E2FC9-9ECE-4B84-83EC-3B5A7BABEB7A:2
,2016-04-01 10:37:20.776 ThaliTest[2666:4852557] multipeer manager: restart client
,2016-04-01 10:37:20.789 ThaliTest[2666:4852557] client: found existing peer: 7A3E2FC9-9ECE-4B84-83EC-3B5A7BABEB7A:2
,2016-04-01 10:37:40.776 ThaliTest[2666:4852557] multipeer manager: restart client
,2016-04-01 10:37:40.787 ThaliTest[2666:4852557] client: found existing peer: 7A3E2FC9-9ECE-4B84-83EC-3B5A7BABEB7A:2
,2016-04-01 10:38:00.776 ThaliTest[2666:4852557] multipeer manager: restart client
,2016-04-01 10:38:00.787 ThaliTest[2666:4852557] client: found existing peer: 7A3E2FC9-9ECE-4B84-83EC-3B5A7BABEB7A:2
,2016-04-01 10:38:20.776 ThaliTest[2666:4852557] multipeer manager: restart client
,2016-04-01 10:38:20.789 ThaliTest[2666:4852557] client: found existing peer: 7A3E2FC9-9ECE-4B84-83EC-3B5A7BABEB7A:2
,2016-04-01 10:38:40.776 ThaliTest[2666:4852557] multipeer manager: restart client
,2016-04-01 10:38:40.789 ThaliTest[2666:4852557] client: found existing peer: 7A3E2FC9-9ECE-4B84-83EC-3B5A7BABEB7A:2
,2016-04-01 10:39:00.776 ThaliTest[2666:4852557] multipeer manager: restart client
,2016-04-01 10:39:00.784 ThaliTest[2666:4852557] client: found existing peer: 7A3E2FC9-9ECE-4B84-83EC-3B5A7BABEB7A:2
,2016-04-01 10:39:20.776 ThaliTest[2666:4852557] multipeer manager: restart client
,2016-04-01 10:39:20.790 ThaliTest[2666:4852557] client: found existing peer: 7A3E2FC9-9ECE-4B84-83EC-3B5A7BABEB7A:2
,2016-04-01 10:39:40.776 ThaliTest[2666:4852557] multipeer manager: restart client
,2016-04-01 10:39:40.789 ThaliTest[2666:4852557] client: found existing peer: 7A3E2FC9-9ECE-4B84-83EC-3B5A7BABEB7A:2
,2016-04-01 10:40:00.776 ThaliTest[2666:4852557] multipeer manager: restart client
,2016-04-01 10:40:00.794 ThaliTest[2666:4852557] client: found existing peer: 7A3E2FC9-9ECE-4B84-83EC-3B5A7BABEB7A:2
,2016-04-01 10:40:20.776 ThaliTest[2666:4852557] multipeer manager: restart client
,2016-04-01 10:40:20.796 ThaliTest[2666:4852557] client: found existing peer: 7A3E2FC9-9ECE-4B84-83EC-3B5A7BABEB7A:2
,2016-04-01 10:40:40.776 ThaliTest[2666:4852557] multipeer manager: restart client
,2016-04-01 10:40:40.788 ThaliTest[2666:4852557] client: found existing peer: 7A3E2FC9-9ECE-4B84-83EC-3B5A7BABEB7A:2
,2016-04-01 10:41:00.776 ThaliTest[2666:4852557] multipeer manager: restart client
,2016-04-01 10:41:00.787 ThaliTest[2666:4852557] client: found existing peer: 7A3E2FC9-9ECE-4B84-83EC-3B5A7BABEB7A:2
,2016-04-01 10:41:20.776 ThaliTest[2666:4852557] multipeer manager: restart client
,2016-04-01 10:41:20.787 ThaliTest[2666:4852557] client: found existing peer: 7A3E2FC9-9ECE-4B84-83EC-3B5A7BABEB7A:2
,2016-04-01 10:41:40.776 ThaliTest[2666:4852557] multipeer manager: restart client
,2016-04-01 10:41:40.790 ThaliTest[2666:4852557] client: found existing peer: 7A3E2FC9-9ECE-4B84-83EC-3B5A7BABEB7A:2
,2016-04-01 10:42:00.776 ThaliTest[2666:4852557] multipeer manager: restart client
,2016-04-01 10:42:00.788 ThaliTest[2666:4852557] client: found existing peer: 7A3E2FC9-9ECE-4B84-83EC-3B5A7BABEB7A:2
,2016-04-01 10:42:20.776 ThaliTest[2666:4852557] multipeer manager: restart client
,2016-04-01 10:42:20.788 ThaliTest[2666:4852557] client: found existing peer: 7A3E2FC9-9ECE-4B84-83EC-3B5A7BABEB7A:2
,2016-04-01 10:42:40.776 ThaliTest[2666:4852557] multipeer manager: restart client
,2016-04-01 10:42:40.789 ThaliTest[2666:4852557] client: found existing peer: 7A3E2FC9-9ECE-4B84-83EC-3B5A7BABEB7A:2
,2016-04-01 10:43:00.776 ThaliTest[2666:4852557] multipeer manager: restart client
,2016-04-01 10:43:00.788 ThaliTest[2666:4852557] client: found existing peer: 7A3E2FC9-9ECE-4B84-83EC-3B5A7BABEB7A:2
,2016-04-01 10:43:20.776 ThaliTest[2666:4852557] multipeer manager: restart client
,2016-04-01 10:43:20.789 ThaliTest[2666:4852557] client: found existing peer: 7A3E2FC9-9ECE-4B84-83EC-3B5A7BABEB7A:2
,2016-04-01 10:43:40.776 ThaliTest[2666:4852557] multipeer manager: restart client
,2016-04-01 10:43:40.880 ThaliTest[2666:4852557] client: found existing peer: 7A3E2FC9-9ECE-4B84-83EC-3B5A7BABEB7A:2
,2016-04-01 10:44:00.776 ThaliTest[2666:4852557] multipeer manager: restart client
,2016-04-01 10:44:00.787 ThaliTest[2666:4852557] client: found existing peer: 7A3E2FC9-9ECE-4B84-83EC-3B5A7BABEB7A:2
,2016-04-01 10:44:20.776 ThaliTest[2666:4852557] multipeer manager: restart client
,2016-04-01 10:44:20.788 ThaliTest[2666:4852557] client: found existing peer: 7A3E2FC9-9ECE-4B84-83EC-3B5A7BABEB7A:2
,2016-04-01 10:44:40.776 ThaliTest[2666:4852557] multipeer manager: restart client
,2016-04-01 10:44:40.789 ThaliTest[2666:4852557] client: found existing peer: 7A3E2FC9-9ECE-4B84-83EC-3B5A7BABEB7A:2
,2016-04-01 10:45:00.754 ThaliTest[2666:4852557] multipeer manager: restart client
,2016-04-01 10:45:00.764 ThaliTest[2666:4852557] client: found existing peer: 7A3E2FC9-9ECE-4B84-83EC-3B5A7BABEB7A:2
,2016-04-01 10:45:20.754 ThaliTest[2666:4852557] multipeer manager: restart client
,2016-04-01 10:45:20.779 ThaliTest[2666:4852557] client: found existing peer: 7A3E2FC9-9ECE-4B84-83EC-3B5A7BABEB7A:2
,2016-04-01 10:45:40.754 ThaliTest[2666:4852557] multipeer manager: restart client
,2016-04-01 10:45:40.774 ThaliTest[2666:4852557] client: found existing peer: 7A3E2FC9-9ECE-4B84-83EC-3B5A7BABEB7A:2
,2016-04-01 10:46:00.754 ThaliTest[2666:4852557] multipeer manager: restart client
,2016-04-01 10:46:00.765 ThaliTest[2666:4852557] client: found existing peer: 7A3E2FC9-9ECE-4B84-83EC-3B5A7BABEB7A:2
,2016-04-01 10:46:20.754 ThaliTest[2666:4852557] multipeer manager: restart client
,2016-04-01 10:46:20.773 ThaliTest[2666:4852557] client: found existing peer: 7A3E2FC9-9ECE-4B84-83EC-3B5A7BABEB7A:2
,2016-04-01 10:46:40.753 ThaliTest[2666:4852557] multipeer manager: restart client
,2016-04-01 10:46:40.766 ThaliTest[2666:4852557] client: found existing peer: 7A3E2FC9-9ECE-4B84-83EC-3B5A7BABEB7A:2
,2016-04-01 10:46:48.865 ThaliTest[2666:4852557] client: lost peer: 7A3E2FC9-9ECE-4B84-83EC-3B5A7BABEB7A
2016-04-01 10:46:48.866 ThaliTest[2666:4852557] client session: onPeerLost: 7A3E2FC9-9ECE-4B84-83EC-3B5A7BABEB7A
,2016-04-01 10:47:00.754 ThaliTest[2666:4852557] multipeer manager: restart client
,2016-04-01 10:47:00.764 ThaliTest[2666:4852557] client: found existing peer: 7A3E2FC9-9ECE-4B84-83EC-3B5A7BABEB7A:2
,2016-04-01 10:47:20.754 ThaliTest[2666:4852557] multipeer manager: restart client
,2016-04-01 10:47:20.763 ThaliTest[2666:4852557] client: found existing peer: 7A3E2FC9-9ECE-4B84-83EC-3B5A7BABEB7A:2
,2016-04-01 10:47:40.754 ThaliTest[2666:4852557] multipeer manager: restart client
,2016-04-01 10:47:40.764 ThaliTest[2666:4852557] client: found existing peer: 7A3E2FC9-9ECE-4B84-83EC-3B5A7BABEB7A:2
,2016-04-01 10:48:00.753 ThaliTest[2666:4852557] multipeer manager: restart client
,2016-04-01 10:48:00.763 ThaliTest[2666:4852557] client: found existing peer: 7A3E2FC9-9ECE-4B84-83EC-3B5A7BABEB7A:2
,2016-04-01 10:48:20.753 ThaliTest[2666:4852557] multipeer manager: restart client
,2016-04-01 10:48:20.764 ThaliTest[2666:4852557] client: found existing peer: 7A3E2FC9-9ECE-4B84-83EC-3B5A7BABEB7A:2

```
