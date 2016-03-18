#### Test 63377149f0d5e10_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/63377149f0d5e10/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/5FC9B7BE-ADFA-4553-9149-C8D0E8DF8BEA/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/5FC9B7BE-ADFA-4553-9149-C8D0E8DF8BEA/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/63377149f0d5e10/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/63377149f0d5e10/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/CDA35F75-A12D-4526-BBEA-2B2A07F6BAB0/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52632"
,(lldb)     command script import "/tmp/5FC9B7BE-ADFA-4553-9149-C8D0E8DF8BEA/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-03-18 15:47:28.835 ThaliTest[1730:2833070] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/DDD78F40-27A9-4136-9403-C7569A2D9D66/Library/Cookies/Cookies.binarycookies
,2016-03-18 15:47:29.311 ThaliTest[1730:2833070] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-18 15:47:29.313 ThaliTest[1730:2833070] Multi-tasking -> Device: YES, App: YES
,2016-03-18 15:47:29.335 ThaliTest[1730:2833070] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-18 15:47:31.372 ThaliTest[1730:2833070] Using UIWebView
,2016-03-18 15:47:31.380 ThaliTest[1730:2833070] [CDVTimer][handleopenurl] 0.707030ms
,2016-03-18 15:47:31.389 ThaliTest[1730:2833070] [CDVTimer][intentandnavigationfilter] 8.935988ms
,2016-03-18 15:47:31.391 ThaliTest[1730:2833070] [CDVTimer][gesturehandler] 0.441968ms
2016-03-18 15:47:31.391 ThaliTest[1730:2833070] [CDVTimer][TotalPluginStartup] 11.959970ms
,2016-03-18 15:47:38.974 ThaliTest[1730:2833070] Resetting plugins due to page load.
,2016-03-18 15:47:43.054 ThaliTest[1730:2833070] Finished load of: file:///var/mobile/Containers/Bundle/Application/CDA35F75-A12D-4526-BBEA-2B2A07F6BAB0/ThaliTest.app/www/index.html
,2016-03-18 15:47:43.289 ThaliTest[1730:2833070] JXcore Cordova plugin initializing
2016-03-18 15:47:43.291 ThaliTest[1730:2833293] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-18 15:47:48.445 ThaliTest[1730:2833293] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-18 15:47:48.446 ThaliTest[1730:2833293] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-18 15:47:48.446 ThaliTest[1730:2833293] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-18 15:47:48.449 ThaliTest[1730:2833293] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone5s-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CDA35F75-A12D-4526-BBEA-2B2A07F6BAB0/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CDA35F75-A12D-4526-BBEA-2B2A07F6BAB0/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CDA35F75-A12D-4526-BBEA-2B2A07F6BAB0/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CDA35F75-A12D-4526-BBEA-2B2A07F6BAB0/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CDA35F75-A12D-4526-BBEA-2B2A07F6BAB0/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CDA35F75-A12D-4526-BBEA-2B2A07F6BAB0/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CDA35F75-A12D-4526-BBEA-2B2A07F6BAB0/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CDA35F75-A12D-4526-BBEA-2B2A07F6BAB0/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CDA35F75-A12D-4526-BBEA-2B2A07F6BAB0/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CDA35F75-A12D-4526-BBEA-2B2A07F6BAB0/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CDA35F75-A12D-4526-BBEA-2B2A07F6BAB0/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CDA35F75-A12D-4526-BBEA-2B2A07F6BAB0/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CDA35F75-A12D-4526-BBEA-2B2A07F6BAB0/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CDA35F75-A12D-4526-BBEA-2B2A07F6BAB0/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CDA35F75-A12D-4526-BBEA-2B2A07F6BAB0/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CDA35F75-A12D-4526-BBEA-2B2A07F6BAB0/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CDA35F75-A12D-4526-BBEA-2B2A07F6BAB0/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CDA35F75-A12D-4526-BBEA-2B2A07F6BAB0/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CDA35F75-A12D-4526-BBEA-2B2A07F6BAB0/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/CDA35F75-A12D-4526-BBEA-2B2A07F6BAB0/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-18 15:47:58.891 ThaliTest[1730:2833070] THREAD WARNING: ['JXcore'] took '7495.012207' ms. Plugin should use a background thread.
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
,2016-03-18 15:50:56.193 ThaliTest[1730:2833293] jxcore: startListeningForAdvertisements
,2016-03-18 15:50:56.196 ThaliTest[1730:2833293] multipeer manager: start client restart timer: 0x15ddfd40
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-18 15:50:56.201 ThaliTest[1730:2833293] jxcore: startListeningForAdvertisements: success
ok 129 Can call startListeningForAdvertisements without error
,2016-03-18 15:50:56.212 ThaliTest[1730:2833293] jxcore: stopListeningForAdvertisements
2016-03-18 15:50:56.213 ThaliTest[1730:2833293] multipeer manager: stop client timer
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-18 15:50:56.218 ThaliTest[1730:2833293] jxcore: stopListeningForAdvertisements: success
,ok 130 Can call stopListeningForAdvertisements without error
,# setup
,2016-03-18 15:50:56.456 ThaliTest[1730:2833293] jxcore: stopListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-18 15:50:56.458 ThaliTest[1730:2833293] jxcore: stopListeningForAdvertisements: success
,ok 131 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-18 15:50:56.462 ThaliTest[1730:2833293] jxcore: stopAdvertisingAndListening
2016-03-18 15:50:56.463 ThaliTest[1730:2833293] THEMultipeerManager stopping peer
2016-03-18 15:50:56.463 ThaliTest[1730:2833293] jxcore: stopAdvertisingAndListening: success
ok 132 Should be able to call stopAdvertisingAndListening in teardown
,# 33. Calling startListeningForAdvertisements twice is NOT an error
,# teardown
,2016-03-18 15:50:56.980 ThaliTest[1730:2833293] jxcore: startListeningForAdvertisements
2016-03-18 15:50:56.981 ThaliTest[1730:2833293] multipeer manager: start client restart timer: 0x15ddfd40
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdat,eNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-18 15:50:56.983 ThaliTest[1730:2833293] jxcore: startListeningForAdvertisements: success
,ok 133 Can call startListeningForAdvertisements without error
2016-03-18 15:50:56.988 ThaliTest[1730:2833293] jxcore: startListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-18 15:50:56.994 ThaliTest[1730:2833293] jxcore: startListeningForAdvertisements: success
ok 134 Can call startListeningForAdvertisements twice without error
,# setup
,2016-03-18 15:50:57.127 ThaliTest[1730:2833293] jxcore: stopListeningForAdvertisements
2016-03-18 15:50:57.127 ThaliTest[1730:2833293] multipeer manager: stop client timer
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertising,Active":false,"discoveryActive":false}
,2016-03-18 15:50:57.130 ThaliTest[1730:2833293] jxcore: stopListeningForAdvertisements: success
,ok 135 Should be able to call stopListeningForAdvertisments in teardown
2016-03-18 15:50:57.133 ThaliTest[1730:2833293] jxcore: stopAdvertisingAndListening
2016-03-18 15:50:57.134 ThaliTest[1730:2833293] THEMultipeerManager stopping peer
2016-03-18 15:5,0:57.134 ThaliTest[1730:2833293] jxcore: stopAdvertisingAndListening: success
ok 136 Should be able to call stopAdvertisingAndListening in teardown
,# 34. Can call start/stopUpdateAdvertisingAndListening
,# teardown
,2016-03-18 15:51:00.148 ThaliTest[1730:2833293] jxcore: startUpdateAdvertisingAndListening
2016-03-18 15:51:00.149 ThaliTest[1730:2833293] server: starting FB7229AA-4713-4BED-BA62-4F08FAA3D947:1
2016-03-18 15:51:00.151 ThaliTest[1730:2833293] multipeer m,anager: start client restart timer: 0x15ddfd40
2016-03-18 15:51:00.151 ThaliTest[1730:2833293] THEMultipeerManager initialized peer FB7229AA-4713-4BED-BA62-4F08FAA3D947:1
2016-03-18 15:51:00.152 ThaliTest[1730:2833293] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 137 Can call startUpdateAdvertisingAndListening without error
2016-03-18 15:51:00.156 ThaliTest[1730:2833293] jxcore: stopAdvertisingAndListening
2016-03-18 15:51:00.157 ThaliTest[1730:2833293] THEMultipeerManager stopping peer
2016,-03-18 15:51:00.157 ThaliTest[1730:2833293] multipeer manager: stop client timer
2016-03-18 15:51:00.158 ThaliTest[1730:2833293] jxcore: stopAdvertisingAndListening: success
,ok 138 Can call stopAdvertisingAndListening without error
,# setup
,2016-03-18 15:51:00.272 ThaliTest[1730:2833293] jxcore: stopListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-18 15:51:00.275 ThaliTest[1730:2833293] jxcore: stopListeningForAdvertisements: success
,ok 139 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-18 15:51:00.278 ThaliTest[1730:2833293] jxcore: stopAdvertisingAndListening
2016-03-18 15:51:00.278 ThaliTest[1730:2833293] THEMultipeerManager stopping peer
2016-03-18 15:51:00.279 ThaliTest[1730:2833293] jxcore: stopAdvertisingAndListening: suc,cess
ok 140 Should be able to call stopAdvertisingAndListening in teardown
,# 35. Calling startUpdateAdvertisingAndListening twice is NOT an error
,# teardown
,2016-03-18 15:51:00.689 ThaliTest[1730:2833293] jxcore: startUpdateAdvertisingAndListening
2016-03-18 15:51:00.690 ThaliTest[1730:2833293] server: starting FB7229AA-4713-4BED-BA62-4F08FAA3D947:2
2016-03-18 15:51:00.691 ThaliTest[1730:2833293] multipeer m,anager: start client restart timer: 0x15ddfd40
2016-03-18 15:51:00.691 ThaliTest[1730:2833293] THEMultipeerManager initialized peer FB7229AA-4713-4BED-BA62-4F08FAA3D947:2
2016-03-18 15:51:00.692 ThaliTest[1730:2833293] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 141 Can call startUpdateAdvertisingAndListening without error
2016-03-18 15:51:00.694 ThaliTest[1730:2833293] jxcore: startUpdateAdvertisingAndListening
,2016-03-18 15:51:00.695 ThaliTest[1730:2833293] THEMultipeerManager stopping peer
,2016-03-18 15:51:00.716 ThaliTest[1730:2833293] multipeer manager: stop client timer
,2016-03-18 15:51:00.720 ThaliTest[1730:2833293] server: starting FB7229AA-4713-4BED-BA62-4F08FAA3D947:3
,2016-03-18 15:51:00.730 ThaliTest[1730:2833293] multipeer manager: start client restart timer: 0x15ddfd40
,2016-03-18 15:51:00.736 ThaliTest[1730:2833293] THEMultipeerManager initialized peer FB7229AA-4713-4BED-BA62-4F08FAA3D947:3
,2016-03-18 15:51:00.738 ThaliTest[1730:2833293] jxcore: startUpdateAdvertisingAndListening: success
,ok 142 Can call startUpdateAdvertisingAndListening twice without error
,# setup
,2016-03-18 15:51:00.868 ThaliTest[1730:2833293] jxcore: stopListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-18 15:51:00.871 ThaliTest[1730:2833293] jxcore: stopListeningForAdvertisements: success
,ok 143 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-18 15:51:00.874 ThaliTest[1730:2833293] jxcore: stopAdvertisingAndListening
2016-03-18 15:51:00.875 ThaliTest[1730:2833293] THEMultipeerManager stopping peer
2016-03-18 15:51:00.875 ThaliTest[1730:2833293] multipeer manager: stop client timer
20,16-03-18 15:51:00.876 ThaliTest[1730:2833293] jxcore: stopAdvertisingAndListening: success
ok 144 Should be able to call stopAdvertisingAndListening in teardown
,# 36. peerAvailabilityChange is called
,# teardown
,2016-03-18 15:51:01.270 ThaliTest[1730:2833293] jxcore: startUpdateAdvertisingAndListening
2016-03-18 15:51:01.270 ThaliTest[1730:2833293] server: starting FB7229AA-4713-4BED-BA62-4F08FAA3D947:4
2016-03-18 15:51:01.271 ThaliTest[1730:2833293] multipeer m,anager: start client restart timer: 0x15ddfd40
2016-03-18 15:51:01.272 ThaliTest[1730:2833293] THEMultipeerManager initialized peer FB7229AA-4713-4BED-BA62-4F08FAA3D947:4
2016-03-18 15:51:01.272 ThaliTest[1730:2833293] jxcore: startUpdateAdvertisingAndListening: success
,ok 145 Can call startUpdateAdvertisingAndListeningwithout error
,2016-03-18 15:51:01.276 ThaliTest[1730:2833293] jxcore: startListeningForAdvertisements
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-18 15:51:01.279 ThaliTest[1730:2833293], jxcore: startListeningForAdvertisements: success
ok 146 Can call startListeningForAdvertisements without error
,2016-03-18 15:51:02.318 ThaliTest[1730:2833070] client: found new peer: 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
ok 147 peers must be an array
ok 148 peers must not be zero-length
,ok 149 peer must have peerIdentifier
ok 150 peerIdentifier must be a string
,ok 151 peer must have peerAvailable
,ok 152 peer must have pleaseConnect
,# setup
,2016-03-18 15:51:03.862 ThaliTest[1730:2833293] jxcore: stopListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-18 15:51:03.864 ThaliTest[1730:2833293] jxcore: stopListeningForAdvertisements: success
ok 153 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-18 15:51:03.869 ThaliTest[1730:2833293] jxcore: stopAdvertisingAndListening
2016-03-18 15:51:03.870 ThaliTest[1730:2833293] THEMultipeerManager stopping peer
2016-03-18 15:51:03.870 ThaliTest[1730:2833293] multipeer manager: stop client timer
2016-03-18 15:51:03.871 ThaliTest[1730:2833293] jxcore: stopAdvertisingAndListening: success
ok 154 Should be able to call stopAdvertisingAndListening in teardown
,# 37. Can connect to a remote peer
,# teardown
,2016-03-18 15:51:18.561 ThaliTest[1730:2833293] jxcore: startUpdateAdvertisingAndListening
2016-03-18 15:51:18.561 ThaliTest[1730:2833293] server: starting FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
,2016-03-18 15:51:18.562 ThaliTest[1730:2833293] multipeer manager: start client restart timer: 0x15ddfd40
2016-03-18 15:51:18.564 ThaliTest[1730:2833293] THEMultipeerManager initialized peer FB7229AA-4713-4BED-BA62-4F08FAA3D947:5
2016-03-18 15:51:18.565 ,ThaliTest[1730:2833293] jxcore: startUpdateAdvertisingAndListening: success
ok 155 Can call startUpdateAdvertisingAndListening without error
,2016-03-18 15:51:18.567 ThaliTest[1730:2833293] jxcore: startListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-18 15:51:18.571 ThaliTest[1730:2833293] jxcore: startListeningForAdvertisements: success
ok 156 Can call startListeningForAdvertisements without error
,2016-03-18 15:51:19.408 ThaliTest[1730:2833070] client: found new peer: 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
,INFO testThaliMobileNative Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4","pleaseConnect":0}]
2016-03-18 15:51:19.422 ThaliTest[1730:2833293] jxcore: connect 5AF2D5AA-97F0-4EB5-AB,41-40475ADCED46:4
2016-03-18 15:51:19.423 ThaliTest[1730:2833293] client session: connect
2016-03-18 15:51:19.424 ThaliTest[1730:2833293] client session: stateChange:0->1 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
,2016-03-18 15:51:21.094 ThaliTest[1730:2833070] multipeer session: reset timer
2016-03-18 15:51:21.094 ThaliTest[1730:2833070] server: rejecting invitation for lexical ordering 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46
INFO testThaliMobileNative Received peer,AvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:5","pleaseConnect":1}]
,2016-03-18 15:51:21.117 ThaliTest[1730:2833675] client session: not connected 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
2016-03-18 15:51:21.117 ThaliTest[1730:2833675] client session: onLinkFailure: 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46
2016-03-18 15:51:21.1,17 ThaliTest[1730:2833675] client session: disconnect
2016-03-18 15:51:21.119 ThaliTest[1730:2833675] client session: stateChange:1->0 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
2016-03-18 15:51:21.120 ThaliTest[1730:2833675] client session: fireConnectCallb,ack: 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46
2016-03-18 15:51:21.121 ThaliTest[1730:2833675] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative Connect returned an error: Peer disconnected
INFO testThaliMobileNative Scheduling a connect re,try - retries left: 9
,2016-03-18 15:51:24.129 ThaliTest[1730:2833293] jxcore: connect 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
2016-03-18 15:51:24.130 ThaliTest[1730:2833293] client session: connect
2016-03-18 15:51:24.130 ThaliTest[1730:2833293] client session: stateChange:0->1 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
,2016-03-18 15:51:24.654 ThaliTest[1730:2833724] client session: not connected 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
,2016-03-18 15:51:24.655 ThaliTest[1730:2833724] client session: onLinkFailure: 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46
,2016-03-18 15:51:24.656 ThaliTest[1730:2833724] client session: disconnect
,2016-03-18 15:51:24.656 ThaliTest[1730:2833724] client session: stateChange:1->0 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
,2016-03-18 15:51:24.658 ThaliTest[1730:2833724] client session: fireConnectCallback: 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46
,2016-03-18 15:51:24.658 ThaliTest[1730:2833724] jxcore: connect: fail: Peer disconnected
,INFO testThaliMobileNative Connect returned an error: Peer disconnected
,INFO testThaliMobileNative Scheduling a connect retry - retries left: 8
,2016-03-18 15:51:27.672 ThaliTest[1730:2833293] jxcore: connect 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
2016-03-18 15:51:27.673 ThaliTest[1730:2833293] client session: connect
2016-03-18 15:51:27.674 ThaliTest[1730:2833293] client session: stateChange:0->1 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
,2016-03-18 15:51:28.356 ThaliTest[1730:2833675] client session: not connected 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
2016-03-18 15:51:28.357 ThaliTest[1730:2833675] client session: onLinkFailure: 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46
2016-03-18 15:51:28.357 ThaliTest[1730:2833675] client session: disconnect
,2016-03-18 15:51:28.357 ThaliTest[1730:2833675] client session: stateChange:1->0 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
,2016-03-18 15:51:28.362 ThaliTest[1730:2833675] client session: fireConnectCallback: 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46
2016-03-18 15:51:28.363 ThaliTest[1730:2833675] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative Connect returned, an error: Peer disconnected
INFO testThaliMobileNative Scheduling a connect retry - retries left: 7
,2016-03-18 15:51:31.370 ThaliTest[1730:2833293] jxcore: connect 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
2016-03-18 15:51:31.371 ThaliTest[1730:2833293] client session: connect
2016-03-18 15:51:31.371 ThaliTest[1730:2833293] client session: stateChange:0->,1 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
,2016-03-18 15:51:31.899 ThaliTest[1730:2833724] client session: not connected 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
2016-03-18 15:51:31.900 ThaliTest[1730:2833724] client session: onLinkFailure: 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46
2016-03-18 15:51:31.9,00 ThaliTest[1730:2833724] client session: disconnect
2016-03-18 15:51:31.900 ThaliTest[1730:2833724] client session: stateChange:1->0 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
2016-03-18 15:51:31.901 ThaliTest[1730:2833724] client session: fireConnectCallb,ack: 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46
2016-03-18 15:51:31.902 ThaliTest[1730:2833724] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative Connect returned an error: Peer disconnected
INFO testThaliMobileNative Scheduling a connect re,try - retries left: 6
,2016-03-18 15:51:34.081 ThaliTest[1730:2833070] multipeer session: reset timer
,2016-03-18 15:51:34.082 ThaliTest[1730:2833070] server: disconnecting to refresh session (5AF2D5AA-97F0-4EB5-AB41-40475ADCED46)
2016-03-18 15:51:34.082 ThaliTest[1730:2833070] server: rejecting invitation for lexical ordering 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46
,INFO testThaliMobileNative Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:5","pleaseConnect":1}]
,2016-03-18 15:51:34.911 ThaliTest[1730:2833293] jxcore: connect 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
2016-03-18 15:51:34.912 ThaliTest[1730:2833293] client session: connect
2016-03-18 15:51:34.913 ThaliTest[1730:2833293] client session: stateChange:0->,1 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
,2016-03-18 15:51:35.538 ThaliTest[1730:2833724] client session: not connected 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
2016-03-18 15:51:35.544 ThaliTest[1730:2833724] client session: onLinkFailure: 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46
2016-03-18 15:51:35.5,44 ThaliTest[1730:2833724] client session: disconnect
2016-03-18 15:51:35.544 ThaliTest[1730:2833724] client session: stateChange:1->0 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
2016-03-18 15:51:35.545 ThaliTest[1730:2833724] client session: fireConnectCallb,ack: 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46
2016-03-18 15:51:35.546 ThaliTest[1730:2833724] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative Connect returned an error: Peer disconnected
INFO testThaliMobileNative Scheduling a connect retry - retries left: 5
,2016-03-18 15:51:38.556 ThaliTest[1730:2833293] jxcore: connect 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
,2016-03-18 15:51:38.557 ThaliTest[1730:2833293] client session: connect
2016-03-18 15:51:38.558 ThaliTest[1730:2833293] client session: stateChange:0->1 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
,2016-03-18 15:51:38.565 ThaliTest[1730:2833070] multipeer manager: restart client
,2016-03-18 15:51:38.582 ThaliTest[1730:2833070] client: lost peer: 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46
2016-03-18 15:51:38.582 ThaliTest[1730:2833070] client session: onPeerLost: 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46
2016-03-18 15:51:38.583 ThaliTest[173,0:2833070] client session: onLinkFailure: 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46
2016-03-18 15:51:38.586 ThaliTest[1730:2833070] client session: disconnect
2016-03-18 15:51:38.586 ThaliTest[1730:2833070] client session: stateChange:1->0 5AF2D5AA-97F0-4EB5-,AB41-40475ADCED46:4
,2016-03-18 15:51:38.590 ThaliTest[1730:2833070] client session: fireConnectCallback: 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46
2016-03-18 15:51:38.591 ThaliTest[1730:2833070] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative Connect returned, an error: Peer disconnected
INFO testThaliMobileNative Scheduling a connect retry - retries left: 4
,2016-03-18 15:51:38.609 ThaliTest[1730:2833070] client: found existing peer: 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
,INFO testThaliMobileNative Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4","pleaseConnect":0}]
,2016-03-18 15:51:41.604 ThaliTest[1730:2833293] jxcore: connect 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
2016-03-18 15:51:41.605 ThaliTest[1730:2833293] client session: connect
2016-03-18 15:51:41.605 ThaliTest[1730:2833293] client session: stateChange:0->1 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
,2016-03-18 15:51:42.313 ThaliTest[1730:2833754] client session: not connected 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
2016-03-18 15:51:42.314 ThaliTest[1730:2833754] client session: onLinkFailure: 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46
2016-03-18 15:51:42.3,14 ThaliTest[1730:2833754] client session: disconnect
2016-03-18 15:51:42.315 ThaliTest[1730:2833754] client session: stateChange:1->0 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
,2016-03-18 15:51:42.320 ThaliTest[1730:2833754] client session: fireConnectCallback: 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46
2016-03-18 15:51:42.320 ThaliTest[1730:2833754] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative Connect returned, an error: Peer disconnected
INFO testThaliMobileNative Scheduling a connect retry - retries left: 3
,2016-03-18 15:51:45.329 ThaliTest[1730:2833293] jxcore: connect 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
2016-03-18 15:51:45.329 ThaliTest[1730:2833293] client session: connect
2016-03-18 15:51:45.330 ThaliTest[1730:2833293] client session: stateChange:0->,1 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
,2016-03-18 15:51:46.080 ThaliTest[1730:2833724] client session: not connected 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
2016-03-18 15:51:46.081 ThaliTest[1730:2833724] client session: onLinkFailure: 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46
2016-03-18 15:51:46.0,81 ThaliTest[1730:2833724] client session: disconnect
2016-03-18 15:51:46.082 ThaliTest[1730:2833724] client session: stateChange:1->0 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
2016-03-18 15:51:46.082 ThaliTest[1730:2833724] client session: fireConnectCallb,ack: 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46
2016-03-18 15:51:46.083 ThaliTest[1730:2833724] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative Connect returned an error: Peer disconnected
INFO testThaliMobileNative Scheduling a connect retry - retries left: 2
,2016-03-18 15:51:46.738 ThaliTest[1730:2833070] multipeer session: reset timer
2016-03-18 15:51:46.739 ThaliTest[1730:2833070] server: disconnecting to refresh session (5AF2D5AA-97F0-4EB5-AB41-40475ADCED46)
2016-03-18 15:51:46.739 ThaliTest[1730:2833070], server: rejecting invitation for lexical ordering 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46
INFO testThaliMobileNative Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:5","pleaseConnect":1}]
,2016-03-18 15:51:49.089 ThaliTest[1730:2833293] jxcore: connect 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
2016-03-18 15:51:49.089 ThaliTest[1730:2833293] client session: connect
2016-03-18 15:51:49.090 ThaliTest[1730:2833293] client session: stateChange:0->,1 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
,2016-03-18 15:51:49.729 ThaliTest[1730:2833675] client session: not connected 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
2016-03-18 15:51:49.729 ThaliTest[1730:2833675] client session: onLinkFailure: 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46
2016-03-18 15:51:49.7,29 ThaliTest[1730:2833675] client session: disconnect
2016-03-18 15:51:49.730 ThaliTest[1730:2833675] client session: stateChange:1->0 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
,2016-03-18 15:51:49.734 ThaliTest[1730:2833675] client session: fireConnectCallback: 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46
2016-03-18 15:51:49.734 ThaliTest[1730:2833675] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative Connect returned an error: Peer disconnected
INFO testThaliMobileNative Scheduling a connect retry - retries left: 1
,2016-03-18 15:51:52.745 ThaliTest[1730:2833293] jxcore: connect 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
2016-03-18 15:51:52.746 ThaliTest[1730:2833293] client session: connect
2016-03-18 15:51:52.746 ThaliTest[1730:2833293] client session: stateChange:0->1 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
,2016-03-18 15:51:53.397 ThaliTest[1730:2833683] client session: not connected 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
2016-03-18 15:51:53.397 ThaliTest[1730:2833683] client session: onLinkFailure: 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46
2016-03-18 15:51:53.3,98 ThaliTest[1730:2833683] client session: disconnect
2016-03-18 15:51:53.398 ThaliTest[1730:2833683] client session: stateChange:1->0 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
2016-03-18 15:51:53.400 ThaliTest[1730:2833683] client session: fireConnectCallb,ack: 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46
2016-03-18 15:51:53.401 ThaliTest[1730:2833683] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative Connect returned an error: Peer disconnected
WARN testThaliMobileNative Too many connect retrie,s!
,2016-03-18 15:51:58.566 ThaliTest[1730:2833070] multipeer manager: restart client
,2016-03-18 15:51:58.592 ThaliTest[1730:2833070] client: found existing peer: 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
,2016-03-18 15:51:59.874 ThaliTest[1730:2833070] multipeer session: reset timer
2016-03-18 15:51:59.874 ThaliTest[1730:2833070] server: disconnecting to refresh session (5AF2D5AA-97F0-4EB5-AB41-40475ADCED46)
2016-03-18 15:51:59.874 ThaliTest[1730:2833070], server: rejecting invitation for lexical ordering 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46
INFO testThaliMobileNative Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:5","pleaseConnect":1}]
,2016-03-18 15:52:13.149 ThaliTest[1730:2833070] multipeer session: reset timer
2016-03-18 15:52:13.149 ThaliTest[1730:2833070] server: disconnecting to refresh session (5AF2D5AA-97F0-4EB5-AB41-40475ADCED46)
2016-03-18 15:52:13.150 ThaliTest[1730:2833070], server: rejecting invitation for lexical ordering 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46
INFO testThaliMobileNative Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:5","pleaseConnect":1}]
,2016-03-18 15:52:18.566 ThaliTest[1730:2833070] multipeer manager: restart client
,2016-03-18 15:52:18.591 ThaliTest[1730:2833070] client: found existing peer: 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
,2016-03-18 15:52:26.342 ThaliTest[1730:2833070] multipeer session: reset timer
2016-03-18 15:52:26.343 ThaliTest[1730:2833070] server: disconnecting to refresh session (5AF2D5AA-97F0-4EB5-AB41-40475ADCED46)
2016-03-18 15:52:26.343 ThaliTest[1730:2833070], server: rejecting invitation for lexical ordering 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46
INFO testThaliMobileNative Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:5","pleaseConnect":1,}]
,2016-03-18 15:52:38.566 ThaliTest[1730:2833070] multipeer manager: restart client
,2016-03-18 15:52:38.589 ThaliTest[1730:2833070] client: found existing peer: 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
,2016-03-18 15:52:39.578 ThaliTest[1730:2833070] multipeer session: reset timer
2016-03-18 15:52:39.578 ThaliTest[1730:2833070] server: disconnecting to refresh session (5AF2D5AA-97F0-4EB5-AB41-40475ADCED46)
2016-03-18 15:52:39.579 ThaliTest[1730:2833070], server: rejecting invitation for lexical ordering 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46
INFO testThaliMobileNative Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:5","pleaseConnect":1}]
,2016-03-18 15:52:52.152 ThaliTest[1730:2833070] multipeer session: reset timer
2016-03-18 15:52:52.153 ThaliTest[1730:2833070] server: disconnecting to refresh session (5AF2D5AA-97F0-4EB5-AB41-40475ADCED46)
2016-03-18 15:52:52.153 ThaliTest[1730:2833070], server: rejecting invitation for lexical ordering 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46
INFO testThaliMobileNative Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:5","pleaseConnect":1,}]
,2016-03-18 15:52:58.566 ThaliTest[1730:2833070] multipeer manager: restart client
,2016-03-18 15:52:58.589 ThaliTest[1730:2833070] client: found existing peer: 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
,2016-03-18 15:53:05.270 ThaliTest[1730:2833070] multipeer session: reset timer
2016-03-18 15:53:05.270 ThaliTest[1730:2833070] server: disconnecting to refresh session (5AF2D5AA-97F0-4EB5-AB41-40475ADCED46)
2016-03-18 15:53:05.270 ThaliTest[1730:2833070], server: rejecting invitation for lexical ordering 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46
INFO testThaliMobileNative Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:5","pleaseConnect":1}]
,2016-03-18 15:53:18.503 ThaliTest[1730:2833070] multipeer session: reset timer
2016-03-18 15:53:18.504 ThaliTest[1730:2833070] server: disconnecting to refresh session (5AF2D5AA-97F0-4EB5-AB41-40475ADCED46)
2016-03-18 15:53:18.504 ThaliTest[1730:2833070], server: rejecting invitation for lexical ordering 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46
INFO testThaliMobileNative Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:5","pleaseConnect":1}]
,2016-03-18 15:53:18.566 ThaliTest[1730:2833070] multipeer manager: restart client
,2016-03-18 15:53:18.591 ThaliTest[1730:2833070] client: found existing peer: 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
,2016-03-18 15:53:38.566 ThaliTest[1730:2833070] multipeer manager: restart client
,2016-03-18 15:53:38.591 ThaliTest[1730:2833070] client: found existing peer: 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
,2016-03-18 15:53:58.566 ThaliTest[1730:2833070] multipeer manager: restart client
,2016-03-18 15:53:58.592 ThaliTest[1730:2833070] client: found existing peer: 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
,2016-03-18 15:54:18.566 ThaliTest[1730:2833070] multipeer manager: restart client
,2016-03-18 15:54:18.591 ThaliTest[1730:2833070] client: found existing peer: 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
,2016-03-18 15:54:38.566 ThaliTest[1730:2833070] multipeer manager: restart client
,2016-03-18 15:54:38.592 ThaliTest[1730:2833070] client: found updated peer: 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:5
INFO testThaliMobileNative Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"5AF2D5AA-97F0-4EB5-AB41-40475A,DCED46:5","pleaseConnect":0}]
,2016-03-18 15:54:58.566 ThaliTest[1730:2833070] multipeer manager: restart client
,2016-03-18 15:54:58.591 ThaliTest[1730:2833070] client: found updated peer: 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
INFO testThaliMobileNative Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4","pleaseConnect":0}]
,2016-03-18 15:55:18.566 ThaliTest[1730:2833070] multipeer manager: restart client
,2016-03-18 15:55:18.590 ThaliTest[1730:2833070] client: found existing peer: 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
,2016-03-18 15:55:38.566 ThaliTest[1730:2833070] multipeer manager: restart client
,2016-03-18 15:55:38.592 ThaliTest[1730:2833070] client: found existing peer: 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
,2016-03-18 15:55:58.566 ThaliTest[1730:2833070] multipeer manager: restart client
,2016-03-18 15:55:58.592 ThaliTest[1730:2833070] client: found existing peer: 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
,2016-03-18 15:56:18.566 ThaliTest[1730:2833070] multipeer manager: restart client
,2016-03-18 15:56:18.592 ThaliTest[1730:2833070] client: found existing peer: 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
,2016-03-18 15:56:38.566 ThaliTest[1730:2833070] multipeer manager: restart client
,2016-03-18 15:56:38.589 ThaliTest[1730:2833070] client: found updated peer: 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:5
INFO testThaliMobileNative Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:5","pleaseConnect":0}]
,2016-03-18 15:56:58.566 ThaliTest[1730:2833070] multipeer manager: restart client
,2016-03-18 15:56:58.591 ThaliTest[1730:2833070] client: found updated peer: 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
INFO testThaliMobileNative Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"5AF2D5AA-97F0-4EB5-AB41-40475A,DCED46:4","pleaseConnect":0}]
,2016-03-18 15:57:18.566 ThaliTest[1730:2833070] multipeer manager: restart client
,2016-03-18 15:57:18.589 ThaliTest[1730:2833070] client: found existing peer: 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
,2016-03-18 15:57:38.566 ThaliTest[1730:2833070] multipeer manager: restart client
,2016-03-18 15:57:38.591 ThaliTest[1730:2833070] client: found existing peer: 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
,2016-03-18 15:57:58.566 ThaliTest[1730:2833070] multipeer manager: restart client
,2016-03-18 15:57:58.592 ThaliTest[1730:2833070] client: found existing peer: 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
,2016-03-18 15:58:18.566 ThaliTest[1730:2833070] multipeer manager: restart client
,2016-03-18 15:58:18.590 ThaliTest[1730:2833070] client: found existing peer: 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
,2016-03-18 15:58:38.566 ThaliTest[1730:2833070] multipeer manager: restart client
,2016-03-18 15:58:38.590 ThaliTest[1730:2833070] client: found updated peer: 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:5
INFO testThaliMobileNative Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:5","pleaseConnect":0}]
,2016-03-18 15:58:58.566 ThaliTest[1730:2833070] multipeer manager: restart client
,2016-03-18 15:58:58.591 ThaliTest[1730:2833070] client: found updated peer: 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
INFO testThaliMobileNative Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"5AF2D5AA-97F0-4EB5-AB41-40475A,DCED46:4","pleaseConnect":0}]
,2016-03-18 15:59:18.565 ThaliTest[1730:2833070] multipeer manager: restart client
,2016-03-18 15:59:18.588 ThaliTest[1730:2833070] client: found existing peer: 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
,2016-03-18 15:59:38.566 ThaliTest[1730:2833070] multipeer manager: restart client
,2016-03-18 15:59:38.589 ThaliTest[1730:2833070] client: found existing peer: 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
,2016-03-18 15:59:58.566 ThaliTest[1730:2833070] multipeer manager: restart client
,2016-03-18 15:59:58.590 ThaliTest[1730:2833070] client: found existing peer: 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
,2016-03-18 16:00:18.566 ThaliTest[1730:2833070] multipeer manager: restart client
,2016-03-18 16:00:18.593 ThaliTest[1730:2833070] client: found existing peer: 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
,2016-03-18 16:00:38.566 ThaliTest[1730:2833070] multipeer manager: restart client
,2016-03-18 16:00:38.588 ThaliTest[1730:2833070] client: found existing peer: 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
,2016-03-18 16:00:58.565 ThaliTest[1730:2833070] multipeer manager: restart client
,2016-03-18 16:00:58.591 ThaliTest[1730:2833070] client: found existing peer: 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
,2016-03-18 16:01:18.566 ThaliTest[1730:2833070] multipeer manager: restart client
,2016-03-18 16:01:18.591 ThaliTest[1730:2833070] client: found existing peer: 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
,2016-03-18 16:01:38.565 ThaliTest[1730:2833070] multipeer manager: restart client
,2016-03-18 16:01:38.589 ThaliTest[1730:2833070] client: found existing peer: 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
,2016-03-18 16:01:58.566 ThaliTest[1730:2833070] multipeer manager: restart client
,2016-03-18 16:01:58.588 ThaliTest[1730:2833070] client: found existing peer: 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
,2016-03-18 16:02:18.566 ThaliTest[1730:2833070] multipeer manager: restart client
,2016-03-18 16:02:18.589 ThaliTest[1730:2833070] client: found existing peer: 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
,2016-03-18 16:02:38.565 ThaliTest[1730:2833070] multipeer manager: restart client
,2016-03-18 16:02:38.589 ThaliTest[1730:2833070] client: found existing peer: 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
,2016-03-18 16:02:58.566 ThaliTest[1730:2833070] multipeer manager: restart client
,2016-03-18 16:02:58.592 ThaliTest[1730:2833070] client: found existing peer: 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
,2016-03-18 16:03:18.566 ThaliTest[1730:2833070] multipeer manager: restart client
,2016-03-18 16:03:18.594 ThaliTest[1730:2833070] client: found existing peer: 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
,2016-03-18 16:03:38.566 ThaliTest[1730:2833070] multipeer manager: restart client
,2016-03-18 16:03:38.590 ThaliTest[1730:2833070] client: found existing peer: 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
,2016-03-18 16:03:58.566 ThaliTest[1730:2833070] multipeer manager: restart client
,2016-03-18 16:03:58.590 ThaliTest[1730:2833070] client: found existing peer: 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
,2016-03-18 16:04:18.566 ThaliTest[1730:2833070] multipeer manager: restart client
,2016-03-18 16:04:18.591 ThaliTest[1730:2833070] client: found existing peer: 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
,2016-03-18 16:04:38.565 ThaliTest[1730:2833070] multipeer manager: restart client
,2016-03-18 16:04:38.587 ThaliTest[1730:2833070] client: found existing peer: 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
,2016-03-18 16:04:58.566 ThaliTest[1730:2833070] multipeer manager: restart client
,2016-03-18 16:04:58.591 ThaliTest[1730:2833070] client: found existing peer: 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
,2016-03-18 16:05:18.566 ThaliTest[1730:2833070] multipeer manager: restart client
,2016-03-18 16:05:18.591 ThaliTest[1730:2833070] client: found existing peer: 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
,2016-03-18 16:05:38.566 ThaliTest[1730:2833070] multipeer manager: restart client
,2016-03-18 16:05:38.591 ThaliTest[1730:2833070] client: found existing peer: 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
,2016-03-18 16:05:58.566 ThaliTest[1730:2833070] multipeer manager: restart client
,2016-03-18 16:05:58.592 ThaliTest[1730:2833070] client: found existing peer: 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
,2016-03-18 16:06:18.566 ThaliTest[1730:2833070] multipeer manager: restart client
,2016-03-18 16:06:18.590 ThaliTest[1730:2833070] client: found existing peer: 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
,2016-03-18 16:06:38.566 ThaliTest[1730:2833070] multipeer manager: restart client
,2016-03-18 16:06:38.591 ThaliTest[1730:2833070] client: found updated peer: 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:5
INFO testThaliMobileNative Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:5","pleaseConnect":0}]
,2016-03-18 16:06:58.565 ThaliTest[1730:2833070] multipeer manager: restart client
,2016-03-18 16:06:58.588 ThaliTest[1730:2833070] client: found updated peer: 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
INFO testThaliMobileNative Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4","pleaseConnect":0}]
,2016-03-18 16:07:18.566 ThaliTest[1730:2833070] multipeer manager: restart client
,2016-03-18 16:07:18.592 ThaliTest[1730:2833070] client: found existing peer: 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
,2016-03-18 16:07:38.566 ThaliTest[1730:2833070] multipeer manager: restart client
,2016-03-18 16:07:38.591 ThaliTest[1730:2833070] client: found existing peer: 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
,2016-03-18 16:07:58.566 ThaliTest[1730:2833070] multipeer manager: restart client
,2016-03-18 16:07:58.592 ThaliTest[1730:2833070] client: found existing peer: 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
,2016-03-18 16:08:18.566 ThaliTest[1730:2833070] multipeer manager: restart client
,2016-03-18 16:08:18.589 ThaliTest[1730:2833070] client: found existing peer: 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
,2016-03-18 16:08:38.566 ThaliTest[1730:2833070] multipeer manager: restart client
,2016-03-18 16:08:38.591 ThaliTest[1730:2833070] client: found existing peer: 5AF2D5AA-97F0-4EB5-AB41-40475ADCED46:4
,2016-03-18 16:08:58.566 ThaliTest[1730:2833070] multipeer manager: restart client

```
