#### Test 63186632d456b18_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/63186632d456b18/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/7E1F86D0-A767-46D0-81B5-E63BDB8706A3/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/7E1F86D0-A767-46D0-81B5-E63BDB8706A3/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/63186632d456b18/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/63186632d456b18/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/D6EBF670-4561-41BD-B02A-B9A8BC62CE43/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51305"
,(lldb)     command script import "/tmp/7E1F86D0-A767-46D0-81B5-E63BDB8706A3/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-17 09:48:59.995 ThaliTest[1644:2644618] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/2FE86CBE-044B-4A6E-88E1-40E7C3837B9A/Library/Cookies/Cookies.binarycookies
,2016-03-17 09:49:00.340 ThaliTest[1644:2644618] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-17 09:49:00.341 ThaliTest[1644:2644618] Multi-tasking -> Device: YES, App: YES
,2016-03-17 09:49:00.361 ThaliTest[1644:2644618] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-17 09:49:02.060 ThaliTest[1644:2644618] Using UIWebView
,2016-03-17 09:49:02.068 ThaliTest[1644:2644618] [CDVTimer][handleopenurl] 0.661016ms
,2016-03-17 09:49:02.077 ThaliTest[1644:2644618] [CDVTimer][intentandnavigationfilter] 8.399010ms
2016-03-17 09:49:02.078 ThaliTest[1644:2644618] [CDVTimer][gesturehandler] 0.413001ms
2016-03-17 09:49:02.078 ThaliTest[1644:2644618] [CDVTimer][TotalPluginS,tartup] 11.256039ms
,2016-03-17 09:49:08.933 ThaliTest[1644:2644618] Resetting plugins due to page load.
,2016-03-17 09:49:12.326 ThaliTest[1644:2644618] Finished load of: file:///var/mobile/Containers/Bundle/Application/D6EBF670-4561-41BD-B02A-B9A8BC62CE43/ThaliTest.app/www/index.html
,2016-03-17 09:49:12.556 ThaliTest[1644:2644618] JXcore Cordova plugin initializing
,2016-03-17 09:49:12.714 ThaliTest[1644:2644846] JXcore instance initializing
Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-17 09:49:17.678 ThaliTest[1644:2644846] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-17 09:49:17.679 ThaliTest[1644:2644846] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-17 09:49:17.679 ThaliTest[1644:2644846] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-17 09:49:17.683 ThaliTest[1644:2644846] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5s-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D6EBF670-4561-41BD-B02A-B9A8BC62CE43/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D6EBF670-4561-41BD-B02A-B9A8BC62CE43/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D6EBF670-4561-41BD-B02A-B9A8BC62CE43/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D6EBF670-4561-41BD-B02A-B9A8BC62CE43/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D6EBF670-4561-41BD-B02A-B9A8BC62CE43/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D6EBF670-4561-41BD-B02A-B9A8BC62CE43/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D6EBF670-4561-41BD-B02A-B9A8BC62CE43/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D6EBF670-4561-41BD-B02A-B9A8BC62CE43/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D6EBF670-4561-41BD-B02A-B9A8BC62CE43/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D6EBF670-4561-41BD-B02A-B9A8BC62CE43/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D6EBF670-4561-41BD-B02A-B9A8BC62CE43/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D6EBF670-4561-41BD-B02A-B9A8BC62CE43/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D6EBF670-4561-41BD-B02A-B9A8BC62CE43/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D6EBF670-4561-41BD-B02A-B9A8BC62CE43/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D6EBF670-4561-41BD-B02A-B9A8BC62CE43/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D6EBF670-4561-41BD-B02A-B9A8BC62CE43/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D6EBF670-4561-41BD-B02A-B9A8BC62CE43/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D6EBF670-4561-41BD-B02A-B9A8BC62CE43/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/D6EBF670-4561-41BD-B02A-B9A8BC62CE43/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-17 09:49:28.218 ThaliTest[1644:2644618] THREAD WARNING: ['JXcore'] took '7559.933105' ms. Plugin should use a background thread.
,Reconnected to the test server
,TAP version 13
,# setup
,# 1. calling createNativeListener directly rejects
,# teardown
,ok 1 Should throw
,# setup
,# 2. emits incomingConnectionState
,# teardown
,ok 2 initial connection state should be CONNECTED
,ok 3 final connection state should be DISCONNECTED
,# setup
,# 3. emits routerPortConnectionFailed
,# teardown
,ok 4 tried to connect to right port
,ok 5 failed due to refused connection
,ok 6 routerPortConnectionFailed is emitted
,# setup
,# 4. native server connections all up
,# teardown
,ok 7 Send/recvd #1 should be equal length
,ok 8 Send/recvd #1 should be same
,ok 9 Send/recvd #2 should be equal length
,ok 10 Send/recvd #2 should be same
,ok 11 Should be exactly 2 client sockets
,# setup
,# 5. native server - closing incoming stream cleans outgoing socket
,# teardown
,ok 12 socket shouldn't close until after stream
,ok 13 incoming remains open
,# setup
,# 6. native server - closing incoming connection cleans outgoing socket
,# teardown
,ok 14 we should not have gotten an error
,ok 15 socket shouldn't close until after incoming
,ok 16 incoming is cleaned up
,# setup
,# 7. native server - closing outgoing socket cleans associated mux stream
,# teardown
,ok 17 stream was closed
,ok 18 incoming should survive
,ok 19 mux should have no streams
,# setup
,# 8. native server - closing the whole server cleans everything up
,# teardown
,ok 20 we should not have gotten an error
,ok 21 Buffers are identical
,ok 22 native server is nulled out
,ok 23 native server should be closed
,ok 24 incoming has been removed
,ok 25 Incoming should be done
,ok 26 The mux object should be closed
,ok 27 The mux stream should be closed
,# setup
,# 9. native server - we can get a ton of connections and data through and still clean up the server completely
,# teardown
,ok 28 native server is nulled out
,ok 29 native server should be closed
,ok 30 incoming has been removed
,# setup
,# 10. native server - simulate mux failure, make sure everything is cleaned up
,# teardown
,ok 31 we should not have gotten an error
,ok 32 Buffers are identical
,ok 33 server should be fine
,ok 34 server should be open
,ok 35 incoming has been removed
,ok 36 The mux object should be closed
,ok 37 The mux stream should be closed
,# setup
,# 11. native server - timing out the incoming connection cleans everything up
,# teardown
,ok 38 we should not have gotten an error
,ok 39 Buffers are identical
,ok 40 server should be fine
,ok 41 server should be open
,ok 42 incoming has been removed
,ok 43 The mux object should be closed
,ok 44 The mux stream should be closed
,# setup
,# 12. closeAll can close even when connections open
,# teardown
,ok 45 not possible to connect to the server anymore
,# setup
,# 13. closeAll with promise
,# teardown
,ok 46 not possible to connect to the server anymore
,# setup
,# 14. multiplex can send data
,# teardown
,ok 47 String should be length:200
,# setup
,# 15. enqueue and run in order
,# teardown
,ok 48 firstPromise setTimeout
,ok 49 firstPromise result
,ok 50 firstPromise testValue
,ok 51 secondPromise setTimeout
,ok 52 secondPromise result
,ok 53 secondPromise testValue
,ok 54 thirdPromise in promise
,ok 55 thirdPromise result
,ok 56 thirdPromise testValue
,# setup
,# 16. enqueueAtTop and run backwards
,# teardown
,ok 57 thirdPromise - first to run
,ok 58 thirdPromise - in resolve
,ok 59 secondPromise - second to run
,ok 60 secondPromise - in catch
,ok 61 firstPromise - third to run
,ok 62 firstPromise - in then
,ok 63 testing promises
,# setup
,# 17. mix enqueue and enqueueAtTop
,# teardown
,ok 64 fourth
,ok 65 fourth
,ok 66 second
,ok 67 secondPromise - in then
,ok 68 first
,ok 69 firstPromise - in catch
,ok 70 third
,ok 71 thirdPromise - in then
,ok 72 testingPromises
,# setup
,# 18. queues handled independently
,# teardown
,ok 73 all short operations completed before the long resolves
,# setup
,# 19. basic
,# teardown
,ok 74 sane
,# setup
,# 20. another
,# teardown
,ok 75 sane
,# setup
,# 21. #startListeningForAdvertisements should fail if start not called
,# teardown
,ok 76 specific error should be returned
,# setup
,ok 77 error should be null
,ok 78 error should be null
,# 22. #startUpdateAdvertisingAndListening should fail if start not called
,# teardown
,ok 79 specific error should be returned
,# setup
,ok 80 error should be null
,ok 81 error should be null
,# 23. should be able to call #stopListeningForAdvertisements many times
,# teardown
,ok 82 error should be null
,ok 83 error should be null
,ok 84 error should be null
,ok 85 error should be null
,# setup
,ok 86 error should be null
,ok 87 error should be null
,# 24. should be able to call #startListeningForAdvertisements many times
,# teardown
,ok 88 error should be null
,ok 89 error should be null
,ok 90 error should be null
,ok 91 error should be null
,# setup
,INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 92 error should be null
,ok 93 error should be null
,# 25. should be able to call #startUpdateAdvertisingAndListening many times
,# teardown
,ok 94 error should be null
,ok 95 error should be null
,ok 96 error should be null
,ok 97 error should be null
,# setup
,INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 98 error should be null
,ok 99 error should be null
,# 26. should be able to call #stopAdvertisingAndListening many times
,# teardown
,ok 100 error should be null
,ok 101 error should be null
,ok 102 error should be null
,ok 103 error should be null
,# setup
,ok 104 error should be null
,ok 105 error should be null
,# 27. #start should fail if called twice in a row
,# teardown
,ok 106 first call should succeed
,ok 107 first call should succeed
,ok 108 specific error should be returned
,# setup
,ok 109 error should be null
,ok 110 error should be null
,# 28. does not emit duplicate discoveryAdvertisingStateUpdate
,# teardown
,ok 111 called only once
,ok 112 discovery state matches
,ok 113 advertising state matches
,# setup
,INFO thaliMobile Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
,INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 114 error should be null
,ok 115 error should be null
,# 29. does not send duplicate availability changes
,# teardown
,ok 116 should be called once
,ok 117 should not have been called more than once
,# setup
,ok 118 error should be null
,ok 119 error should be null
,# 30. can get the network status
,# teardown
,ok 120 network status should have certain non-empty properties
,# setup
,ok 121 error should be null
,ok 122 error should be null
,# 31. wifi peer is marked unavailable if announcements stop
,# teardown
,ok 123 host address should match
,ok 124 port should match
,ok 125 host address should be null
,ok 126 port should should be null
,# setup
,INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 127 error should be null
,ok 128 error should be null
,# 32. Can call start/stopListeningForAdvertisements
,# teardown
,2016-03-17 09:52:52.196 ThaliTest[1644:2644846] jxcore: startListeningForAdvertisements
,2016-03-17 09:52:52.199 ThaliTest[1644:2644846] multipeer manager: start client restart timer: 0x176ad380
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-17 09:52:52.203 ThaliTest[1644:2644846] jxcore: startListeningForAdvertisements: success
,ok 129 Can call startListeningForAdvertisements without error
,2016-03-17 09:52:52.221 ThaliTest[1644:2644846] jxcore: stopListeningForAdvertisements
,2016-03-17 09:52:52.226 ThaliTest[1644:2644846] multipeer manager: stop client timer
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-17 09:52:52.233 ThaliTest[1644:2644846] jxcore: stopListeningForAdvertisements: success
,ok 130 Can call stopListeningForAdvertisements without error
,# setup
,2016-03-17 09:52:52.320 ThaliTest[1644:2644846] jxcore: stopListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-17 09:52:52.324 ThaliTest[1644:2644846] jxcore: stopListeningForAdvertisements: success
,ok 131 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-17 09:52:52.329 ThaliTest[1644:2644846] jxcore: stopAdvertisingAndListening
,2016-03-17 09:52:52.331 ThaliTest[1644:2644846] THEMultipeerManager stopping peer
,2016-03-17 09:52:52.332 ThaliTest[1644:2644846] jxcore: stopAdvertisingAndListening: success
,ok 132 Should be able to call stopAdvertisingAndListening in teardown
,# 33. Calling startListeningForAdvertisements twice is NOT an error
,# teardown
,2016-03-17 09:52:53.087 ThaliTest[1644:2644846] jxcore: startListeningForAdvertisements
2016-03-17 09:52:53.088 ThaliTest[1644:2644846] multipeer manager: start client restart timer: 0x176ad380
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-17 09:52:53.091 ThaliTest[1644:2644846] jxcore: startListeningForAdvertisements: success
ok 133 Can call startListeningForAdvertisements without error
,2016-03-17 09:52:53.095 ThaliTest[1644:2644846] jxcore: startListeningForAdvertisements
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-17 09:52:53.096 ThaliTest[1644:2644846] jxcore: startListeningForAdvertisements: success
,ok 134 Can call startListeningForAdvertisements twice without error
,# setup
,2016-03-17 09:52:53.122 ThaliTest[1644:2644618] client: found new peer: B834405C-4BB1-4DDE-BBBE-95797DDD18CB:5
2016-03-17 09:52:53.124 ThaliTest[1644:2644618] client: found new peer: B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:6
,INFO thaliMobileNativeWrapper peerAvailabilityChanged: [{"peerAvailable":1,"peerIdentifier":"B834405C-4BB1-4DDE-BBBE-95797DDD18CB:5","pleaseConnect":0}]
INFO thaliMobileNativeWrapper peerAvailabilityChanged: [{"peerAvailable":1,"peerIdentifier":"B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:6","pleaseConnect":0}]
,2016-03-17 09:52:53.206 ThaliTest[1644:2644846] jxcore: stopListeningForAdvertisements
,2016-03-17 09:52:53.211 ThaliTest[1644:2644846] multipeer manager: stop client timer
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-17 09:52:53.219 ThaliTest[1644:2644846] jxcore: stopListeningForAdvertisements: success
,ok 135 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-17 09:52:53.223 ThaliTest[1644:2644846] jxcore: stopAdvertisingAndListening
,2016-03-17 09:52:53.224 ThaliTest[1644:2644846] THEMultipeerManager stopping peer
,2016-03-17 09:52:53.225 ThaliTest[1644:2644846] jxcore: stopAdvertisingAndListening: success
,ok 136 Should be able to call stopAdvertisingAndListening in teardown
,# 34. Can call start/stopUpdateAdvertisingAndListening
,# teardown
,2016-03-17 09:52:54.037 ThaliTest[1644:2644846] jxcore: startUpdateAdvertisingAndListening
2016-03-17 09:52:54.038 ThaliTest[1644:2644846] server: starting 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:1
2016-03-17 09:52:54.039 ThaliTest[1644:2644846] multipeer m,anager: start client restart timer: 0x176ad380
2016-03-17 09:52:54.040 ThaliTest[1644:2644846] THEMultipeerManager initialized peer 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:1
2016-03-17 09:52:54.040 ThaliTest[1644:2644846] jxcore: startUpdateAdvertisingAndListening: success
,ok 137 Can call startUpdateAdvertisingAndListening without error
2016-03-17 09:52:54.047 ThaliTest[1644:2644846] jxcore: stopAdvertisingAndListening
2016-03-17 09:52:54.047 ThaliTest[1644:2644846] THEMultipeerManager stopping peer
2016-03-17 09:52:54.04,8 ThaliTest[1644:2644846] multipeer manager: stop client timer
2016-03-17 09:52:54.048 ThaliTest[1644:2644846] jxcore: stopAdvertisingAndListening: success
,ok 138 Can call stopAdvertisingAndListening without error
# setup
,2016-03-17 09:52:54.223 ThaliTest[1644:2644846] jxcore: stopListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-17 09:52:54.226 ThaliTest[1644:2644846] jxcore: stopListeningForAdvertisements: success
,ok 139 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-17 09:52:54.229 ThaliTest[1644:2644846] jxcore: stopAdvertisingAndListening
2016-03-17 09:52:54.230 ThaliTest[1644:2644846] THEMultipeerManager stopping peer
2016-03-17 09:52:54.230 ThaliTest[1644:2644846] jxcore: stopAdvertisingAndListening: success
ok 140 Should be able to call stopAdvertisingAndListening in teardown
,# 35. Calling startUpdateAdvertisingAndListening twice is NOT an error
,# teardown
,2016-03-17 09:52:54.682 ThaliTest[1644:2644846] jxcore: startUpdateAdvertisingAndListening
2016-03-17 09:52:54.683 ThaliTest[1644:2644846] server: starting 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:2
2016-03-17 09:52:54.684 ThaliTest[1644:2644846] multipeer m,anager: start client restart timer: 0x176ad380
2016-03-17 09:52:54.685 ThaliTest[1644:2644846] THEMultipeerManager initialized peer 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:2
2016-03-17 09:52:54.685 ThaliTest[1644:2644846] jxcore: startUpdateAdvertisingAndListening: success
,ok 141 Can call startUpdateAdvertisingAndListening without error
2016-03-17 09:52:54.690 ThaliTest[1644:2644846] jxcore: startUpdateAdvertisingAndListening
2016-03-17 09:52:54.690 ThaliTest[1644:2644846] THEMultipeerManager stopping peer
2016-03-17 09:5,2:54.691 ThaliTest[1644:2644846] multipeer manager: stop client timer
2016-03-17 09:52:54.691 ThaliTest[1644:2644846] server: starting 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:3
,2016-03-17 09:52:54.692 ThaliTest[1644:2644846] multipeer manager: start client restart timer: 0x176ad380
2016-03-17 09:52:54.693 ThaliTest[1644:2644846] THEMultipeerManager initialized peer 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:3
,2016-03-17 09:52:54.693 ThaliTest[1644:2644846] jxcore: startUpdateAdvertisingAndListening: success
,ok 142 Can call startUpdateAdvertisingAndListening twice without error
,# setup
,2016-03-17 09:52:54.761 ThaliTest[1644:2644618] client: found new peer: B834405C-4BB1-4DDE-BBBE-95797DDD18CB:5
2016-03-17 09:52:54.762 ThaliTest[1644:2644618] client: found new peer: B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:6
,2016-03-17 09:52:55.020 ThaliTest[1644:2644846] jxcore: stopListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-17 09:52:55.023 ThaliTest[1644:2644846] jxcore: stopListeningForAdvertisements: success
,ok 143 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-17 09:52:55.027 ThaliTest[1644:2644846] jxcore: stopAdvertisingAndListening
2016-03-17 09:52:55.027 ThaliTest[1644:2644846] THEMultipeerManager stopping peer
2016-03-17 09:52:55.028 ThaliTest[1644:2644846] multipeer manager: stop client timer
20,16-03-17 09:52:55.028 ThaliTest[1644:2644846] jxcore: stopAdvertisingAndListening: success
ok 144 Should be able to call stopAdvertisingAndListening in teardown
,# 36. peerAvailabilityChange is called
,# teardown
,2016-03-17 09:52:57.916 ThaliTest[1644:2644846] jxcore: startUpdateAdvertisingAndListening
2016-03-17 09:52:57.916 ThaliTest[1644:2644846] server: starting 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:4
2016-03-17 09:52:57.917 ThaliTest[1644:2644846] multipeer m,anager: start client restart timer: 0x176ad380
2016-03-17 09:52:57.918 ThaliTest[1644:2644846] THEMultipeerManager initialized peer 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:4
2016-03-17 09:52:57.918 ThaliTest[1644:2644846] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 145 Can call startUpdateAdvertisingAndListeningwithout error
,2016-03-17 09:52:57.921 ThaliTest[1644:2644846] jxcore: startListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-17 09:52:57.924 ThaliTest[1644:2644846] jxcore: startListeningForAdvertisements: success
ok 146 Can call startListeningForAdvertisements without error
,2016-03-17 09:52:58.744 ThaliTest[1644:2644618] client: found new peer: B834405C-4BB1-4DDE-BBBE-95797DDD18CB:5
2016-03-17 09:52:58.747 ThaliTest[1644:2644618] client: found new peer: B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:6
ok 147 peers must be an array
o,k 148 peers must not be zero-length
ok 149 peer must have peerIdentifier
,ok 150 peerIdentifier must be a string
,ok 151 peer must have peerAvailable
,ok 152 peer must have pleaseConnect
,# setup
,2016-03-17 09:52:59.275 ThaliTest[1644:2644618] client: found new peer: 2766A7C7-4577-4560-847A-F62CCBA6A141:4
,2016-03-17 09:52:59.468 ThaliTest[1644:2644846] jxcore: stopListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-17 09:52:59.471 ThaliTest[1644:2644846] jxcore: stopListeningForAdvertisements: success
,ok 153 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-17 09:52:59.474 ThaliTest[1644:2644846] jxcore: stopAdvertisingAndListening
2016-03-17 09:52:59.474 ThaliTest[1644:2644846] THEMultipeerManager stopping peer
2016-03-17 09:52:59.475 ThaliTest[1644:2644846] multipeer manager: stop client timer
20,16-03-17 09:52:59.475 ThaliTest[1644:2644846] jxcore: stopAdvertisingAndListening: success
ok 154 Should be able to call stopAdvertisingAndListening in teardown
,# 37. Can connect to a remote peer
,# teardown
,2016-03-17 09:52:59.934 ThaliTest[1644:2644846] jxcore: startUpdateAdvertisingAndListening
2016-03-17 09:52:59.935 ThaliTest[1644:2644846] server: starting 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:5
2016-03-17 09:52:59.936 ThaliTest[1644:2644846] multipeer m,anager: start client restart timer: 0x176ad380
2016-03-17 09:52:59.936 ThaliTest[1644:2644846] THEMultipeerManager initialized peer 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:5
2016-03-17 09:52:59.937 ThaliTest[1644:2644846] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 155 Can call startUpdateAdvertisingAndListening without error
,2016-03-17 09:52:59.940 ThaliTest[1644:2644846] jxcore: startListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-17 09:52:59.944 ThaliTest[1644:2644846] jxcore: startListeningForAdvertisements: success
ok 156 Can call startListeningForAdvertisements without error
,2016-03-17 09:53:00.622 ThaliTest[1644:2644618] client: found new peer: B834405C-4BB1-4DDE-BBBE-95797DDD18CB:5
2016-03-17 09:53:00.624 ThaliTest[1644:2644618] client: found new peer: B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:6
INFO testThaliMobileNative Recei,ved peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"B834405C-4BB1-4DDE-BBBE-95797DDD18CB:5","pleaseConnect":0}]
,2016-03-17 09:53:00.627 ThaliTest[1644:2644846] jxcore: connect B834405C-4BB1-4DDE-BBBE-95797DDD18CB:5
2016-03-17 09:53:00.631 ThaliTest[1644:2644846] client: server will connect
2016-03-17 09:53:00.632 ThaliTest[1644:2644846] client session: reverseConn,ect
2016-03-17 09:53:00.633 ThaliTest[1644:2644846] client session: stateChange:0->1 B834405C-4BB1-4DDE-BBBE-95797DDD18CB:5
,INFO testThaliMobileNative Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:6","pleaseConnect":0}]
,2016-03-17 09:53:00.697 ThaliTest[1644:2644618] client: found new peer: 2766A7C7-4577-4560-847A-F62CCBA6A141:4
,INFO testThaliMobileNative Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"2766A7C7-4577-4560-847A-F62CCBA6A141:4","pleaseConnect":0}]
,2016-03-17 09:53:02.396 ThaliTest[1644:2644618] multipeer session: reset timer
2016-03-17 09:53:02.396 ThaliTest[1644:2644618] server: rejecting invitation from 2766A7C7-4577-4560-847A-F62CCBA6A141 due to previous generation (18009BE9-5DE3-42DE-8B21-9C164A8A04D8:5 != 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:4)
,2016-03-17 09:53:05.535 ThaliTest[1644:2644618] multipeer session: reset timer
2016-03-17 09:53:05.535 ThaliTest[1644:2644618] server: disconnecting to refresh session (2766A7C7-4577-4560-847A-F62CCBA6A141)
2016-03-17 09:53:05.536 ThaliTest[1644:2644618], server: rejecting invitation from 2766A7C7-4577-4560-847A-F62CCBA6A141 due to previous generation (18009BE9-5DE3-42DE-8B21-9C164A8A04D8:5 != 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:4)
,2016-03-17 09:53:08.819 ThaliTest[1644:2644618] multipeer session: reset timer
2016-03-17 09:53:08.820 ThaliTest[1644:2644618] server: disconnecting to refresh session (2766A7C7-4577-4560-847A-F62CCBA6A141)
2016-03-17 09:53:08.820 ThaliTest[1644:2644618], server: rejecting invitation from 2766A7C7-4577-4560-847A-F62CCBA6A141 due to previous generation (18009BE9-5DE3-42DE-8B21-9C164A8A04D8:5 != 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:4)
,2016-03-17 09:53:10.633 ThaliTest[1644:2644618] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative Scheduling a connect retry - retries left: 9
,2016-03-17 09:53:10.743 ThaliTest[1644:2644618] client: lost peer: B834405C-4BB1-4DDE-BBBE-95797DDD18CB
2016-03-17 09:53:10.743 ThaliTest[1644:2644618] client session: onPeerLost: B834405C-4BB1-4DDE-BBBE-95797DDD18CB
2016-03-17 09:53:10.744 ThaliTest[164,4:2644618] client session: onLinkFailure: B834405C-4BB1-4DDE-BBBE-95797DDD18CB
2016-03-17 09:53:10.744 ThaliTest[1644:2644618] client session: disconnect
2016-03-17 09:53:10.744 ThaliTest[1644:2644618] client session: stateChange:1->0 B834405C-4BB1-4DDE-,BBBE-95797DDD18CB:5
2016-03-17 09:53:10.745 ThaliTest[1644:2644618] client session: no connect callback (server initiated)
,2016-03-17 09:53:12.597 ThaliTest[1644:2644618] multipeer session: reset timer
2016-03-17 09:53:12.598 ThaliTest[1644:2644618] server: disconnecting to refresh session (2766A7C7-4577-4560-847A-F62CCBA6A141)
2016-03-17 09:53:12.598 ThaliTest[1644:2644618], server: rejecting invitation from 2766A7C7-4577-4560-847A-F62CCBA6A141 due to previous generation (18009BE9-5DE3-42DE-8B21-9C164A8A04D8:5 != 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:4)
,2016-03-17 09:53:13.645 ThaliTest[1644:2644846] jxcore: connect B834405C-4BB1-4DDE-BBBE-95797DDD18CB:5
2016-03-17 09:53:13.646 ThaliTest[1644:2644846] client: connect: unreachable B834405C-4BB1-4DDE-BBBE-95797DDD18CB
2016-03-17 09:53:13.646 ThaliTest[164,4:2644846] jxcore: connect: fail: Peer unreachable
INFO testThaliMobileNative Connect returned an error: Peer unreachable
,INFO testThaliMobileNative Scheduling a connect retry - retries left: 8
,2016-03-17 09:53:16.016 ThaliTest[1644:2644618] multipeer session: reset timer
2016-03-17 09:53:16.016 ThaliTest[1644:2644618] server: disconnecting to refresh session (2766A7C7-4577-4560-847A-F62CCBA6A141)
2016-03-17 09:53:16.017 ThaliTest[1644:2644618], server: rejecting invitation from 2766A7C7-4577-4560-847A-F62CCBA6A141 due to previous generation (18009BE9-5DE3-42DE-8B21-9C164A8A04D8:5 != 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:4)
,2016-03-17 09:53:16.657 ThaliTest[1644:2644846] jxcore: connect B834405C-4BB1-4DDE-BBBE-95797DDD18CB:5
2016-03-17 09:53:16.658 ThaliTest[1644:2644846] client: connect: unreachable B834405C-4BB1-4DDE-BBBE-95797DDD18CB
2016-03-17 09:53:16.658 ThaliTest[164,4:2644846] jxcore: connect: fail: Peer unreachable
INFO testThaliMobileNative Connect returned an error: Peer unreachable
INFO testThaliMobileNative Scheduling a connect retry - retries left: 7
,2016-03-17 09:53:19.171 ThaliTest[1644:2644618] multipeer session: reset timer
2016-03-17 09:53:19.172 ThaliTest[1644:2644618] server: disconnecting to refresh session (2766A7C7-4577-4560-847A-F62CCBA6A141)
2016-03-17 09:53:19.172 ThaliTest[1644:2644618], server: rejecting invitation from 2766A7C7-4577-4560-847A-F62CCBA6A141 due to previous generation (18009BE9-5DE3-42DE-8B21-9C164A8A04D8:5 != 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:4)
,2016-03-17 09:53:19.673 ThaliTest[1644:2644846] jxcore: connect B834405C-4BB1-4DDE-BBBE-95797DDD18CB:5
2016-03-17 09:53:19.674 ThaliTest[1644:2644846] client: connect: unreachable B834405C-4BB1-4DDE-BBBE-95797DDD18CB
2016-03-17 09:53:19.674 ThaliTest[164,4:2644846] jxcore: connect: fail: Peer unreachable
INFO testThaliMobileNative Connect returned an error: Peer unreachable
,INFO testThaliMobileNative Scheduling a connect retry - retries left: 6
,2016-03-17 09:53:19.938 ThaliTest[1644:2644618] multipeer manager: restart client
,2016-03-17 09:53:19.968 ThaliTest[1644:2644618] client: found updated peer: 2766A7C7-4577-4560-847A-F62CCBA6A141:5
2016-03-17 09:53:19.969 ThaliTest[1644:2644618] client: found existing peer: B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:6
INFO testThaliMobileNat,ive Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"2766A7C7-4577-4560-847A-F62CCBA6A141:5","pleaseConnect":0}]
,2016-03-17 09:53:22.511 ThaliTest[1644:2644618] multipeer session: reset timer
2016-03-17 09:53:22.512 ThaliTest[1644:2644618] server: disconnecting to refresh session (2766A7C7-4577-4560-847A-F62CCBA6A141)
2016-03-17 09:53:22.512 ThaliTest[1644:2644618], server: rejecting invitation from 2766A7C7-4577-4560-847A-F62CCBA6A141 due to previous generation (18009BE9-5DE3-42DE-8B21-9C164A8A04D8:5 != 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:4)
,2016-03-17 09:53:22.690 ThaliTest[1644:2644846] jxcore: connect B834405C-4BB1-4DDE-BBBE-95797DDD18CB:5
2016-03-17 09:53:22.691 ThaliTest[1644:2644846] client: connect: unreachable B834405C-4BB1-4DDE-BBBE-95797DDD18CB
2016-03-17 09:53:22.692 ThaliTest[164,4:2644846] jxcore: connect: fail: Peer unreachable
INFO testThaliMobileNative Connect returned an error: Peer unreachable
INFO testThaliMobileNative Scheduling a connect retry - retries left: 5
,2016-03-17 09:53:25.700 ThaliTest[1644:2644846] jxcore: connect B834405C-4BB1-4DDE-BBBE-95797DDD18CB:5
2016-03-17 09:53:25.701 ThaliTest[1644:2644846] client: connect: unreachable B834405C-4BB1-4DDE-BBBE-95797DDD18CB
2016-03-17 09:53:25.702 ThaliTest[164,4:2644846] jxcore: connect: fail: Peer unreachable
INFO testThaliMobileNative Connect returned an error: Peer unreachable
INFO testThaliMobileNative Scheduling a connect retry - retries left: 4
,2016-03-17 09:53:25.832 ThaliTest[1644:2644618] multipeer session: reset timer
2016-03-17 09:53:25.833 ThaliTest[1644:2644618] server: disconnecting to refresh session (2766A7C7-4577-4560-847A-F62CCBA6A141)
2016-03-17 09:53:25.833 ThaliTest[1644:2644618], server: rejecting invitation from 2766A7C7-4577-4560-847A-F62CCBA6A141 due to previous generation (18009BE9-5DE3-42DE-8B21-9C164A8A04D8:5 != 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:4)
,2016-03-17 09:53:28.717 ThaliTest[1644:2644846] jxcore: connect B834405C-4BB1-4DDE-BBBE-95797DDD18CB:5
2016-03-17 09:53:28.717 ThaliTest[1644:2644846] client: connect: unreachable B834405C-4BB1-4DDE-BBBE-95797DDD18CB
2016-03-17 09:53:28.718 ThaliTest[164,4:2644846] jxcore: connect: fail: Peer unreachable
INFO testThaliMobileNative Connect returned an error: Peer unreachable
INFO testThaliMobileNative Scheduling a connect retry - retries left: 3
,2016-03-17 09:53:29.421 ThaliTest[1644:2644618] multipeer session: reset timer
2016-03-17 09:53:29.421 ThaliTest[1644:2644618] server: disconnecting to refresh session (2766A7C7-4577-4560-847A-F62CCBA6A141)
2016-03-17 09:53:29.422 ThaliTest[1644:2644618], server: rejecting invitation from 2766A7C7-4577-4560-847A-F62CCBA6A141 due to previous generation (18009BE9-5DE3-42DE-8B21-9C164A8A04D8:5 != 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:4)
,2016-03-17 09:53:31.737 ThaliTest[1644:2644846] jxcore: connect B834405C-4BB1-4DDE-BBBE-95797DDD18CB:5
2016-03-17 09:53:31.738 ThaliTest[1644:2644846] client: connect: unreachable B834405C-4BB1-4DDE-BBBE-95797DDD18CB
2016-03-17 09:53:31.739 ThaliTest[164,4:2644846] jxcore: connect: fail: Peer unreachable
INFO testThaliMobileNative Connect returned an error: Peer unreachable
,INFO testThaliMobileNative Scheduling a connect retry - retries left: 2
,2016-03-17 09:53:32.629 ThaliTest[1644:2644618] multipeer session: reset timer
2016-03-17 09:53:32.631 ThaliTest[1644:2644618] server: disconnecting to refresh session (2766A7C7-4577-4560-847A-F62CCBA6A141)
2016-03-17 09:53:32.631 ThaliTest[1644:2644618], server: rejecting invitation from 2766A7C7-4577-4560-847A-F62CCBA6A141 due to previous generation (18009BE9-5DE3-42DE-8B21-9C164A8A04D8:5 != 18009BE9-5DE3-42DE-8B21-9C164A8A04D8:4)
,2016-03-17 09:53:34.758 ThaliTest[1644:2644846] jxcore: connect B834405C-4BB1-4DDE-BBBE-95797DDD18CB:5
2016-03-17 09:53:34.759 ThaliTest[1644:2644846] client: connect: unreachable B834405C-4BB1-4DDE-BBBE-95797DDD18CB
2016-03-17 09:53:34.759 ThaliTest[164,4:2644846] jxcore: connect: fail: Peer unreachable
INFO testThaliMobileNative Connect returned an error: Peer unreachable
INFO testThaliMobileNative Scheduling a connect retry - retries left: 1
,2016-03-17 09:53:37.776 ThaliTest[1644:2644846] jxcore: connect B834405C-4BB1-4DDE-BBBE-95797DDD18CB:5
2016-03-17 09:53:37.777 ThaliTest[1644:2644846] client: connect: unreachable B834405C-4BB1-4DDE-BBBE-95797DDD18CB
2016-03-17 09:53:37.777 ThaliTest[164,4:2644846] jxcore: connect: fail: Peer unreachable
INFO testThaliMobileNative Connect returned an error: Peer unreachable
WARN testThaliMobileNative Too many connect retries!
,2016-03-17 09:53:39.938 ThaliTest[1644:2644618] multipeer manager: restart client
,2016-03-17 09:53:39.969 ThaliTest[1644:2644618] client: found existing peer: B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:6
,2016-03-17 09:53:39.971 ThaliTest[1644:2644618] client: found existing peer: 2766A7C7-4577-4560-847A-F62CCBA6A141:5
,2016-03-17 09:53:59.938 ThaliTest[1644:2644618] multipeer manager: restart client
,2016-03-17 09:53:59.971 ThaliTest[1644:2644618] client: found existing peer: B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:6
2016-03-17 09:53:59.972 ThaliTest[1644:2644618] client: found existing peer: 2766A7C7-4577-4560-847A-F62CCBA6A141:5
,2016-03-17 09:54:19.938 ThaliTest[1644:2644618] multipeer manager: restart client
,2016-03-17 09:54:19.967 ThaliTest[1644:2644618] client: found existing peer: 2766A7C7-4577-4560-847A-F62CCBA6A141:5
2016-03-17 09:54:19.968 ThaliTest[1644:2644618] client: found existing peer: B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:6
,2016-03-17 09:54:39.938 ThaliTest[1644:2644618] multipeer manager: restart client
,2016-03-17 09:54:39.971 ThaliTest[1644:2644618] client: found existing peer: B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:6
2016-03-17 09:54:39.972 ThaliTest[1644:2644618] client: found existing peer: 2766A7C7-4577-4560-847A-F62CCBA6A141:5
,2016-03-17 09:54:59.938 ThaliTest[1644:2644618] multipeer manager: restart client
,2016-03-17 09:54:59.969 ThaliTest[1644:2644618] client: found existing peer: B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:6
,2016-03-17 09:54:59.971 ThaliTest[1644:2644618] client: found existing peer: 2766A7C7-4577-4560-847A-F62CCBA6A141:5
,2016-03-17 09:55:19.938 ThaliTest[1644:2644618] multipeer manager: restart client
,2016-03-17 09:55:19.967 ThaliTest[1644:2644618] client: found existing peer: B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D:6
,2016-03-17 09:55:19.971 ThaliTest[1644:2644618] client: found existing peer: 2766A7C7-4577-4560-847A-F62CCBA6A141:5
,2016-03-17 09:55:37.659 ThaliTest[1644:2644618] client: lost peer: B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D
2016-03-17 09:55:37.659 ThaliTest[1644:2644618] client session: onPeerLost: B3E5E16C-F6AC-48A7-AEDD-2B3D06013F6D
,2016-03-17 09:55:39.938 ThaliTest[1644:2644618] multipeer manager: restart client
,2016-03-17 09:55:39.962 ThaliTest[1644:2644618] client: found existing peer: 2766A7C7-4577-4560-847A-F62CCBA6A141:5
,2016-03-17 09:55:59.938 ThaliTest[1644:2644618] multipeer manager: restart client
,2016-03-17 09:55:59.961 ThaliTest[1644:2644618] client: found existing peer: 2766A7C7-4577-4560-847A-F62CCBA6A141:5
,2016-03-17 09:56:19.938 ThaliTest[1644:2644618] multipeer manager: restart client
,2016-03-17 09:56:19.965 ThaliTest[1644:2644618] client: found existing peer: 2766A7C7-4577-4560-847A-F62CCBA6A141:5
,2016-03-17 09:56:39.938 ThaliTest[1644:2644618] multipeer manager: restart client
,2016-03-17 09:56:39.965 ThaliTest[1644:2644618] client: found existing peer: 2766A7C7-4577-4560-847A-F62CCBA6A141:5
,2016-03-17 09:56:59.938 ThaliTest[1644:2644618] multipeer manager: restart client
,2016-03-17 09:56:59.961 ThaliTest[1644:2644618] client: found existing peer: 2766A7C7-4577-4560-847A-F62CCBA6A141:5
,2016-03-17 09:57:19.938 ThaliTest[1644:2644618] multipeer manager: restart client
,2016-03-17 09:57:19.962 ThaliTest[1644:2644618] client: found existing peer: 2766A7C7-4577-4560-847A-F62CCBA6A141:5
,2016-03-17 09:57:39.938 ThaliTest[1644:2644618] multipeer manager: restart client
,2016-03-17 09:57:39.961 ThaliTest[1644:2644618] client: found existing peer: 2766A7C7-4577-4560-847A-F62CCBA6A141:5
,2016-03-17 09:57:59.938 ThaliTest[1644:2644618] multipeer manager: restart client
,2016-03-17 09:57:59.965 ThaliTest[1644:2644618] client: found existing peer: 2766A7C7-4577-4560-847A-F62CCBA6A141:5
,2016-03-17 09:58:19.938 ThaliTest[1644:2644618] multipeer manager: restart client
,2016-03-17 09:58:19.962 ThaliTest[1644:2644618] client: found existing peer: 2766A7C7-4577-4560-847A-F62CCBA6A141:5
,2016-03-17 09:58:39.938 ThaliTest[1644:2644618] multipeer manager: restart client
,2016-03-17 09:58:39.962 ThaliTest[1644:2644618] client: found existing peer: 2766A7C7-4577-4560-847A-F62CCBA6A141:5
,2016-03-17 09:58:59.938 ThaliTest[1644:2644618] multipeer manager: restart client
,2016-03-17 09:58:59.959 ThaliTest[1644:2644618] client: found existing peer: 2766A7C7-4577-4560-847A-F62CCBA6A141:5
,2016-03-17 09:59:19.938 ThaliTest[1644:2644618] multipeer manager: restart client
,2016-03-17 09:59:19.962 ThaliTest[1644:2644618] client: found existing peer: 2766A7C7-4577-4560-847A-F62CCBA6A141:5
,2016-03-17 09:59:39.938 ThaliTest[1644:2644618] multipeer manager: restart client
,2016-03-17 09:59:39.965 ThaliTest[1644:2644618] client: found existing peer: 2766A7C7-4577-4560-847A-F62CCBA6A141:5
,2016-03-17 09:59:59.938 ThaliTest[1644:2644618] multipeer manager: restart client
,2016-03-17 09:59:59.962 ThaliTest[1644:2644618] client: found existing peer: 2766A7C7-4577-4560-847A-F62CCBA6A141:5
,2016-03-17 10:00:19.937 ThaliTest[1644:2644618] multipeer manager: restart client
,2016-03-17 10:00:39.938 ThaliTest[1644:2644618] multipeer manager: restart client
,2016-03-17 10:00:39.962 ThaliTest[1644:2644618] client: found existing peer: 2766A7C7-4577-4560-847A-F62CCBA6A141:5
,2016-03-17 10:00:59.938 ThaliTest[1644:2644618] multipeer manager: restart client
,2016-03-17 10:00:59.964 ThaliTest[1644:2644618] client: found existing peer: 2766A7C7-4577-4560-847A-F62CCBA6A141:5
,2016-03-17 10:01:19.938 ThaliTest[1644:2644618] multipeer manager: restart client
,2016-03-17 10:01:19.962 ThaliTest[1644:2644618] client: found existing peer: 2766A7C7-4577-4560-847A-F62CCBA6A141:5
,2016-03-17 10:01:39.937 ThaliTest[1644:2644618] multipeer manager: restart client
,2016-03-17 10:01:39.959 ThaliTest[1644:2644618] client: found existing peer: 2766A7C7-4577-4560-847A-F62CCBA6A141:5
,2016-03-17 10:01:59.938 ThaliTest[1644:2644618] multipeer manager: restart client
,2016-03-17 10:01:59.962 ThaliTest[1644:2644618] client: found existing peer: 2766A7C7-4577-4560-847A-F62CCBA6A141:5
,2016-03-17 10:02:19.938 ThaliTest[1644:2644618] multipeer manager: restart client
,2016-03-17 10:02:19.962 ThaliTest[1644:2644618] client: found existing peer: 2766A7C7-4577-4560-847A-F62CCBA6A141:5
,2016-03-17 10:02:39.938 ThaliTest[1644:2644618] multipeer manager: restart client
,2016-03-17 10:02:39.961 ThaliTest[1644:2644618] client: found existing peer: 2766A7C7-4577-4560-847A-F62CCBA6A141:5
,2016-03-17 10:02:59.937 ThaliTest[1644:2644618] multipeer manager: restart client
,2016-03-17 10:02:59.961 ThaliTest[1644:2644618] client: found existing peer: 2766A7C7-4577-4560-847A-F62CCBA6A141:5
,2016-03-17 10:03:19.938 ThaliTest[1644:2644618] multipeer manager: restart client
,2016-03-17 10:03:19.961 ThaliTest[1644:2644618] client: found existing peer: 2766A7C7-4577-4560-847A-F62CCBA6A141:5
,2016-03-17 10:03:39.938 ThaliTest[1644:2644618] multipeer manager: restart client
,2016-03-17 10:03:39.963 ThaliTest[1644:2644618] client: found existing peer: 2766A7C7-4577-4560-847A-F62CCBA6A141:5
,2016-03-17 10:03:59.938 ThaliTest[1644:2644618] multipeer manager: restart client
,2016-03-17 10:03:59.961 ThaliTest[1644:2644618] client: found existing peer: 2766A7C7-4577-4560-847A-F62CCBA6A141:5
,2016-03-17 10:04:19.937 ThaliTest[1644:2644618] multipeer manager: restart client
,2016-03-17 10:04:19.961 ThaliTest[1644:2644618] client: found existing peer: 2766A7C7-4577-4560-847A-F62CCBA6A141:5
,2016-03-17 10:04:39.938 ThaliTest[1644:2644618] multipeer manager: restart client
,2016-03-17 10:04:39.965 ThaliTest[1644:2644618] client: found existing peer: 2766A7C7-4577-4560-847A-F62CCBA6A141:5
,2016-03-17 10:04:59.938 ThaliTest[1644:2644618] multipeer manager: restart client
,2016-03-17 10:04:59.961 ThaliTest[1644:2644618] client: found existing peer: 2766A7C7-4577-4560-847A-F62CCBA6A141:5
,2016-03-17 10:05:19.938 ThaliTest[1644:2644618] multipeer manager: restart client
,2016-03-17 10:05:19.961 ThaliTest[1644:2644618] client: found existing peer: 2766A7C7-4577-4560-847A-F62CCBA6A141:5
,2016-03-17 10:05:39.938 ThaliTest[1644:2644618] multipeer manager: restart client
,2016-03-17 10:05:39.962 ThaliTest[1644:2644618] client: found existing peer: 2766A7C7-4577-4560-847A-F62CCBA6A141:5
,2016-03-17 10:05:59.938 ThaliTest[1644:2644618] multipeer manager: restart client
,2016-03-17 10:05:59.960 ThaliTest[1644:2644618] client: found existing peer: 2766A7C7-4577-4560-847A-F62CCBA6A141:5
,2016-03-17 10:06:19.938 ThaliTest[1644:2644618] multipeer manager: restart client
,2016-03-17 10:06:19.964 ThaliTest[1644:2644618] client: found existing peer: 2766A7C7-4577-4560-847A-F62CCBA6A141:5
,2016-03-17 10:06:39.938 ThaliTest[1644:2644618] multipeer manager: restart client
,2016-03-17 10:06:39.962 ThaliTest[1644:2644618] client: found existing peer: 2766A7C7-4577-4560-847A-F62CCBA6A141:5
,2016-03-17 10:06:59.938 ThaliTest[1644:2644618] multipeer manager: restart client
,2016-03-17 10:06:59.965 ThaliTest[1644:2644618] client: found existing peer: 2766A7C7-4577-4560-847A-F62CCBA6A141:5
,2016-03-17 10:07:19.938 ThaliTest[1644:2644618] multipeer manager: restart client
,2016-03-17 10:07:19.963 ThaliTest[1644:2644618] client: found existing peer: 2766A7C7-4577-4560-847A-F62CCBA6A141:5
,2016-03-17 10:07:39.938 ThaliTest[1644:2644618] multipeer manager: restart client
,2016-03-17 10:07:39.962 ThaliTest[1644:2644618] client: found existing peer: 2766A7C7-4577-4560-847A-F62CCBA6A141:5
,2016-03-17 10:07:59.938 ThaliTest[1644:2644618] multipeer manager: restart client
,2016-03-17 10:07:59.961 ThaliTest[1644:2644618] client: found existing peer: 2766A7C7-4577-4560-847A-F62CCBA6A141:5
,2016-03-17 10:08:19.938 ThaliTest[1644:2644618] multipeer manager: restart client
,2016-03-17 10:08:19.963 ThaliTest[1644:2644618] client: found existing peer: 2766A7C7-4577-4560-847A-F62CCBA6A141:5
,2016-03-17 10:08:39.938 ThaliTest[1644:2644618] multipeer manager: restart client
,2016-03-17 10:08:39.963 ThaliTest[1644:2644618] client: found existing peer: 2766A7C7-4577-4560-847A-F62CCBA6A141:5
,2016-03-17 10:08:59.938 ThaliTest[1644:2644618] multipeer manager: restart client
,2016-03-17 10:08:59.961 ThaliTest[1644:2644618] client: found existing peer: 2766A7C7-4577-4560-847A-F62CCBA6A141:5
,2016-03-17 10:09:19.938 ThaliTest[1644:2644618] multipeer manager: restart client
,2016-03-17 10:09:19.964 ThaliTest[1644:2644618] client: found existing peer: 2766A7C7-4577-4560-847A-F62CCBA6A141:5
,2016-03-17 10:09:39.937 ThaliTest[1644:2644618] multipeer manager: restart client
,2016-03-17 10:09:39.952 ThaliTest[1644:2644618] client: found existing peer: 2766A7C7-4577-4560-847A-F62CCBA6A141:5
,2016-03-17 10:09:59.938 ThaliTest[1644:2644618] multipeer manager: restart client
,2016-03-17 10:09:59.959 ThaliTest[1644:2644618] client: found existing peer: 2766A7C7-4577-4560-847A-F62CCBA6A141:5
,2016-03-17 10:10:19.938 ThaliTest[1644:2644618] multipeer manager: restart client
,2016-03-17 10:10:19.962 ThaliTest[1644:2644618] client: found existing peer: 2766A7C7-4577-4560-847A-F62CCBA6A141:5
,2016-03-17 10:10:39.938 ThaliTest[1644:2644618] multipeer manager: restart client
,2016-03-17 10:10:39.960 ThaliTest[1644:2644618] client: found existing peer: 2766A7C7-4577-4560-847A-F62CCBA6A141:5

```
