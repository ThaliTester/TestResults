#### Test 62509094141ff10_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/62509094141ff10/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/1EFB23E8-F4EF-4D74-9E86-A6F4B4FF688A/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/1EFB23E8-F4EF-4D74-9E86-A6F4B4FF688A/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/62509094141ff10/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/62509094141ff10/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/93070646-D561-42D5-BB35-7A0B8289338A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51455"
,(lldb)     command script import "/tmp/1EFB23E8-F4EF-4D74-9E86-A6F4B4FF688A/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-17 11:16:29.018 ThaliTest[1611:2583013] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C1483F2F-BB67-4265-9FC4-0FE176C2DA3F/Library/Cookies/Cookies.binarycookies
,2016-03-17 11:16:29.335 ThaliTest[1611:2583013] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-17 11:16:29.336 ThaliTest[1611:2583013] Multi-tasking -> Device: YES, App: YES
,2016-03-17 11:16:29.354 ThaliTest[1611:2583013] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-17 11:16:31.029 ThaliTest[1611:2583013] Using UIWebView
,2016-03-17 11:16:31.036 ThaliTest[1611:2583013] [CDVTimer][handleopenurl] 0.541985ms
,2016-03-17 11:16:31.044 ThaliTest[1611:2583013] [CDVTimer][intentandnavigationfilter] 7.214963ms
2016-03-17 11:16:31.044 ThaliTest[1611:2583013] [CDVTimer][gesturehandler] 0.364006ms
2016-03-17 11:16:31.045 ThaliTest[1611:2583013] [CDVTimer][TotalPluginStartup] 9.756982ms
,2016-03-17 11:16:37.752 ThaliTest[1611:2583013] Resetting plugins due to page load.
,2016-03-17 11:16:41.056 ThaliTest[1611:2583013] Finished load of: file:///var/mobile/Containers/Bundle/Application/93070646-D561-42D5-BB35-7A0B8289338A/ThaliTest.app/www/index.html
,2016-03-17 11:16:41.264 ThaliTest[1611:2583013] JXcore Cordova plugin initializing
,2016-03-17 11:16:41.266 ThaliTest[1611:2583227] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-17 11:16:45.516 ThaliTest[1611:2583227] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-17 11:16:45.516 ThaliTest[1611:2583227] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-17 11:16:45.517 ThaliTest[1611:2583227] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-17 11:16:45.520 ThaliTest[1611:2583227] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone6-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/93070646-D561-42D5-BB35-7A0B8289338A/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/93070646-D561-42D5-BB35-7A0B8289338A/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/93070646-D561-42D5-BB35-7A0B8289338A/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/93070646-D561-42D5-BB35-7A0B8289338A/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/93070646-D561-42D5-BB35-7A0B8289338A/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/93070646-D561-42D5-BB35-7A0B8289338A/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/93070646-D561-42D5-BB35-7A0B8289338A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/93070646-D561-42D5-BB35-7A0B8289338A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/93070646-D561-42D5-BB35-7A0B8289338A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/93070646-D561-42D5-BB35-7A0B8289338A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/93070646-D561-42D5-BB35-7A0B8289338A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/93070646-D561-42D5-BB35-7A0B8289338A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/93070646-D561-42D5-BB35-7A0B8289338A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/93070646-D561-42D5-BB35-7A0B8289338A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/93070646-D561-42D5-BB35-7A0B8289338A/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/93070646-D561-42D5-BB35-7A0B8289338A/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/93070646-D561-42D5-BB35-7A0B8289338A/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/93070646-D561-42D5-BB35-7A0B8289338A/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/93070646-D561-42D5-BB35-7A0B8289338A/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-17 11:16:54.335 ThaliTest[1611:2583013] THREAD WARNING: ['JXcore'] took '6339.495117' ms. Plugin should use a background thread.
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
ok 29 native server should be closed
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
,2016-03-17 11:19:51.833 ThaliTest[1611:2583227] jxcore: startListeningForAdvertisements
,2016-03-17 11:19:51.835 ThaliTest[1611:2583227] multipeer manager: start client restart timer: 0x176e6700
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-17 11:19:51.838 ThaliTest[1611:2583227] jxcore: startListeningForAdvertisements: success
,ok 129 Can call startListeningForAdvertisements without error
,2016-03-17 11:19:51.841 ThaliTest[1611:2583227] jxcore: stopListeningForAdvertisements
2016-03-17 11:19:51.842 ThaliTest[1611:2583227] multipeer manager: stop client timer
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertising,Active":false,"discoveryActive":false}
2016-03-17 11:19:51.847 ThaliTest[1611:2583227] jxcore: stopListeningForAdvertisements: success
ok 130 Can call stopListeningForAdvertisements without error
,# setup
,2016-03-17 11:19:52.091 ThaliTest[1611:2583227] jxcore: stopListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-17 11:19:52.094 ThaliTest[1611:2583227] jxcore: stopListeningForAdvertisements: success
,ok 131 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-17 11:19:52.097 ThaliTest[1611:2583227] jxcore: stopAdvertisingAndListening
2016-03-17 11:19:52.097 ThaliTest[1611:2583227] THEMultipeerManager stopping peer
2016-03-17 11:19:52.097 ThaliTest[1611:2583227] jxcore: stopAdvertisingAndListening: suc,cess
ok 132 Should be able to call stopAdvertisingAndListening in teardown
,# 33. Calling startListeningForAdvertisements twice is NOT an error
,# teardown
,2016-03-17 11:19:52.321 ThaliTest[1611:2583227] jxcore: startListeningForAdvertisements
2016-03-17 11:19:52.322 ThaliTest[1611:2583227] multipeer manager: start client restart timer: 0x176e6700
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdat,eNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-17 11:19:52.324 ThaliTest[1611:2583227] jxcore: startListeningForAdvertisements: success
,ok 133 Can call startListeningForAdvertisements without error
,2016-03-17 11:19:52.327 ThaliTest[1611:2583227] jxcore: startListeningForAdvertisements
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-17 11:19:52.329 ThaliTest[1611:2583227,] jxcore: startListeningForAdvertisements: success
ok 134 Can call startListeningForAdvertisements twice without error
,# setup
,2016-03-17 11:19:52.744 ThaliTest[1611:2583227] jxcore: stopListeningForAdvertisements
2016-03-17 11:19:52.744 ThaliTest[1611:2583227] multipeer manager: stop client timer
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-17 11:19:52.747 ThaliTest[1611:2583227] jxcore: stopListeningForAdvertisements: success
ok 135 Should be able to call stopListeningForAdvertisments in teardown
2016-03-17 11:19:52.750 ThaliTest[1611:2583227] jxcore: stopAdvertisingAndListening
2,016-03-17 11:19:52.750 ThaliTest[1611:2583227] THEMultipeerManager stopping peer
2016-03-17 11:19:52.750 ThaliTest[1611:2583227] jxcore: stopAdvertisingAndListening: success
ok 136 Should be able to call stopAdvertisingAndListening in teardown
,# 34. Can call start/stopUpdateAdvertisingAndListening
,# teardown
,2016-03-17 11:19:53.341 ThaliTest[1611:2583227] jxcore: startUpdateAdvertisingAndListening
2016-03-17 11:19:53.342 ThaliTest[1611:2583227] server: starting 20B211DA-8CC3-44A8-A409-C300A017DFDB:1
2016-03-17 11:19:53.343 ThaliTest[1611:2583227] multipeer m,anager: start client restart timer: 0x176e6700
2016-03-17 11:19:53.344 ThaliTest[1611:2583227] THEMultipeerManager initialized peer 20B211DA-8CC3-44A8-A409-C300A017DFDB:1
2016-03-17 11:19:53.344 ThaliTest[1611:2583227] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 137 Can call startUpdateAdvertisingAndListening without error
,2016-03-17 11:19:53.348 ThaliTest[1611:2583227] jxcore: stopAdvertisingAndListening
2016-03-17 11:19:53.350 ThaliTest[1611:2583227] THEMultipeerManager stopping peer
2016-03-17 11:19:53.350 ThaliTest[1611:2583227] multipeer manager: stop client timer
20,16-03-17 11:19:53.351 ThaliTest[1611:2583227] jxcore: stopAdvertisingAndListening: success
ok 138 Can call stopAdvertisingAndListening without error
# setup
,2016-03-17 11:19:53.745 ThaliTest[1611:2583227] jxcore: stopListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-17 11:19:53.747 ThaliTest[1611:2583227] jxcore: stopListeningForAdvertisements: success
,ok 139 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-17 11:19:53.750 ThaliTest[1611:2583227] jxcore: stopAdvertisingAndListening
2016-03-17 11:19:53.751 ThaliTest[1611:2583227] THEMultipeerManager stopping peer
2016-03-17 11:19:53.751 ThaliTest[1611:2583227] jxcore: stopAdvertisingAndListening: suc,cess
ok 140 Should be able to call stopAdvertisingAndListening in teardown
,# 35. Calling startUpdateAdvertisingAndListening twice is NOT an error
,# teardown
,2016-03-17 11:19:54.717 ThaliTest[1611:2583227] jxcore: startUpdateAdvertisingAndListening
2016-03-17 11:19:54.717 ThaliTest[1611:2583227] server: starting 20B211DA-8CC3-44A8-A409-C300A017DFDB:2
2016-03-17 11:19:54.718 ThaliTest[1611:2583227] multipeer m,anager: start client restart timer: 0x176e6700
2016-03-17 11:19:54.719 ThaliTest[1611:2583227] THEMultipeerManager initialized peer 20B211DA-8CC3-44A8-A409-C300A017DFDB:2
2016-03-17 11:19:54.719 ThaliTest[1611:2583227] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 141 Can call startUpdateAdvertisingAndListening without error
2016-03-17 11:19:54.722 ThaliTest[1611:2583227] jxcore: startUpdateAdvertisingAndListening
2016-03-17 11:19:54.722 ThaliTest[1611:2583227] THEMultipeerManager stopping pee,r
2016-03-17 11:19:54.722 ThaliTest[1611:2583227] multipeer manager: stop client timer
2016-03-17 11:19:54.723 ThaliTest[1611:2583227] server: starting 20B211DA-8CC3-44A8-A409-C300A017DFDB:3
2016-03-17 11:19:54.723 ThaliTest[1611:2583227] multipeer mana,ger: start client restart timer: 0x176e6700
,2016-03-17 11:19:54.729 ThaliTest[1611:2583227] THEMultipeerManager initialized peer 20B211DA-8CC3-44A8-A409-C300A017DFDB:3
,2016-03-17 11:19:54.737 ThaliTest[1611:2583227] jxcore: startUpdateAdvertisingAndListening: success
,ok 142 Can call startUpdateAdvertisingAndListening twice without error
# setup
,2016-03-17 11:19:54.843 ThaliTest[1611:2583227] jxcore: stopListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-17 11:19:54.846 ThaliTest[1611:2583227] jxcore: stopListeningForAdvertisements: success
,ok 143 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-17 11:19:54.850 ThaliTest[1611:2583227] jxcore: stopAdvertisingAndListening
,2016-03-17 11:19:54.850 ThaliTest[1611:2583227] THEMultipeerManager stopping peer
,2016-03-17 11:19:54.855 ThaliTest[1611:2583227] multipeer manager: stop client timer
,2016-03-17 11:19:54.857 ThaliTest[1611:2583227] jxcore: stopAdvertisingAndListening: success
,ok 144 Should be able to call stopAdvertisingAndListening in teardown
,# 36. peerAvailabilityChange is called
,# teardown
,2016-03-17 11:19:55.287 ThaliTest[1611:2583227] jxcore: startUpdateAdvertisingAndListening
2016-03-17 11:19:55.287 ThaliTest[1611:2583227] server: starting 20B211DA-8CC3-44A8-A409-C300A017DFDB:4
2016-03-17 11:19:55.288 ThaliTest[1611:2583227] multipeer m,anager: start client restart timer: 0x176e6700
2016-03-17 11:19:55.288 ThaliTest[1611:2583227] THEMultipeerManager initialized peer 20B211DA-8CC3-44A8-A409-C300A017DFDB:4
2016-03-17 11:19:55.289 ThaliTest[1611:2583227] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 145 Can call startUpdateAdvertisingAndListeningwithout error
2016-03-17 11:19:55.291 ThaliTest[1611:2583227] jxcore: startListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
,2016-03-17 11:19:55.294 ThaliTest[1611:2583227] jxcore: startListeningForAdvertisements: success
,ok 146 Can call startListeningForAdvertisements without error
,2016-03-17 11:19:57.427 ThaliTest[1611:2583013] client: found new peer: FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:4
,ok 147 peers must be an array
ok 148 peers must not be zero-length
ok 149 peer must have peerIdentifier
,ok 150 peerIdentifier must be a string
,ok 151 peer must have peerAvailable
,ok 152 peer must have pleaseConnect
,# setup
,2016-03-17 11:19:58.545 ThaliTest[1611:2583227] jxcore: stopListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-17 11:19:58.548 ThaliTest[1611:2583227] jxcore: stopListeningForAdvertisements: success
,ok 153 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-17 11:19:58.550 ThaliTest[1611:2583227] jxcore: stopAdvertisingAndListening
2016-03-17 11:19:58.551 ThaliTest[1611:2583227] THEMultipeerManager stopping peer
,2016-03-17 11:19:58.552 ThaliTest[1611:2583227] multipeer manager: stop client timer
2016-03-17 11:19:58.552 ThaliTest[1611:2583227] jxcore: stopAdvertisingAndListening: success
ok 154 Should be able to call stopAdvertisingAndListening in teardown
# 37. Can connect to a remote peer
,# teardown
,2016-03-17 11:19:59.894 ThaliTest[1611:2583227] jxcore: startUpdateAdvertisingAndListening
2016-03-17 11:19:59.895 ThaliTest[1611:2583227] server: starting 20B211DA-8CC3-44A8-A409-C300A017DFDB:5
,2016-03-17 11:19:59.896 ThaliTest[1611:2583227] multipeer manager: start client restart timer: 0x176e6700
2016-03-17 11:19:59.897 ThaliTest[1611:2583227] THEMultipeerManager initialized peer 20B211DA-8CC3-44A8-A409-C300A017DFDB:5
,2016-03-17 11:19:59.897 ThaliTest[1611:2583227] jxcore: startUpdateAdvertisingAndListening: success
,ok 155 Can call startUpdateAdvertisingAndListening without error
,2016-03-17 11:19:59.900 ThaliTest[1611:2583227] jxcore: startListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-17 11:19:59.903 ThaliTest[1611:2583227] jxcore: startListeningForAdvertisements: success
,ok 156 Can call startListeningForAdvertisements without error
,2016-03-17 11:20:01.861 ThaliTest[1611:2583013] client: found new peer: FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:4
,INFO testThaliMobileNative Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:4","pleaseConnect":0}]
2016-03-17 11:20:01.866 ThaliTest[1611:2583227] jxcore: connect FD1CC9F2-9667-4D2B-A1,14-31A3E1486EC6:4
2016-03-17 11:20:01.866 ThaliTest[1611:2583227] client: server will connect
2016-03-17 11:20:01.867 ThaliTest[1611:2583227] client session: reverseConnect
2016-03-17 11:20:01.867 ThaliTest[1611:2583227] client session: stateChange:0->1, FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:4
,2016-03-17 11:20:11.868 ThaliTest[1611:2583013] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative Scheduling a connect retry - retries left: 9
,2016-03-17 11:20:11.918 ThaliTest[1611:2583013] multipeer session: reset timer
2016-03-17 11:20:11.919 ThaliTest[1611:2583013] server session: connect
2016-03-17 11:20:11.919 ThaliTest[1611:2583013] server session: stateChange:0->1 FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
,2016-03-17 11:20:11.931 ThaliTest[1611:2583013] server: accepting invitation FD1CC9F2-9667-4D2B-A114-31A3E1486EC6
,2016-03-17 11:20:12.310 ThaliTest[1611:2583606] client session: not connected FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:4
2016-03-17 11:20:12.311 ThaliTest[1611:2583606] client session: onLinkFailure: FD1CC9F2-9667-4D2B-A114-31A3E1486EC6
2016-03-17 11:20:12.3,11 ThaliTest[1611:2583606] client session: disconnect
2016-03-17 11:20:12.311 ThaliTest[1611:2583606] client session: stateChange:1->0 FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:4
2016-03-17 11:20:12.312 ThaliTest[1611:2583606] client session: no connect callback (server initiated)
,2016-03-17 11:20:14.886 ThaliTest[1611:2583227] jxcore: connect FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:4
2016-03-17 11:20:14.887 ThaliTest[1611:2583227] client: server already connecting
,2016-03-17 11:20:16.135 ThaliTest[1611:2583696] server session: p2p link connected
,2016-03-17 11:20:16.647 ThaliTest[1611:2583013] server relay: connected (to port: 63464)
2016-03-17 11:20:16.649 ThaliTest[1611:2583013] server session: stateChange:1->2 FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
2016-03-17 11:20:16.649 ThaliTest[1611:2583013] jxcore: connect: success
,INFO testThaliMobileNative 
ok 157 Must have listeningPort
,ok 158 listeningPort must be a number
,ok 159 Connection must have clientPort
,ok 160 clientPort must be a number
,ok 161 Connection must have serverPort
,ok 162 serverPort must be a number
,ok 163 reverse connection must have clientPort != 0
,ok 164 reverse connection must have serverPort != 0
,# setup
,2016-03-17 11:20:17.317 ThaliTest[1611:2583227] jxcore: stopListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-17 11:20:17.319 ThaliTest[1611:2583227] jxcore: stopListeningForAdvertisements: success
,ok 165 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-17 11:20:17.322 ThaliTest[1611:2583227] jxcore: stopAdvertisingAndListening
2016-03-17 11:20:17.322 ThaliTest[1611:2583227] THEMultipeerManager stopping peer
2016-03-17 11:20:17.323 ThaliTest[1611:2583227] server session: disconnect
2016-03-17 1,1:20:17.323 ThaliTest[1611:2583227] server session: stateChange:2->0 FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
,2016-03-17 11:20:17.432 ThaliTest[1611:2583227] multipeer manager: stop client timer
2016-03-17 11:20:17.434 ThaliTest[1611:2583227] jxcore: stopAdvertisingAndListening: success
,ok 166 Should be able to call stopAdvertisingAndListening in teardown
,# 38. Can shift large amounts of data
,# teardown
,2016-03-17 11:20:18.011 ThaliTest[1611:2583227] jxcore: startUpdateAdvertisingAndListening
,2016-03-17 11:20:18.012 ThaliTest[1611:2583227] server: starting 20B211DA-8CC3-44A8-A409-C300A017DFDB:6
,2016-03-17 11:20:18.012 ThaliTest[1611:2583227] multipeer manager: start client restart timer: 0x176e6700
2016-03-17 11:20:18.012 ThaliTest[1611:2583227] THEMultipeerManager initialized peer 20B211DA-8CC3-44A8-A409-C300A017DFDB:6
2016-03-17 11:20:18.012 ,ThaliTest[1611:2583227] jxcore: startUpdateAdvertisingAndListening: success
ok 167 Can call startUpdateAdvertisingAndListening without error
2016-03-17 11:20:18.013 ThaliTest[1611:2583227] jxcore: startListeningForAdvertisements
INFO thaliMobileNativeWr,apper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-17 11:20:18.014 ThaliTest[1611:2583227] jxcore: startListeningForAdvertisements: success
ok 168 Can call startListeningForAdvertisements without error
,2016-03-17 11:20:18.772 ThaliTest[1611:2583013] client: found new peer: FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
2016-03-17 11:20:18.774 ThaliTest[1611:2583227] jxcore: connect FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
2016-03-17 11:20:18.775 ThaliTest[1611:2,583227] client: server will connect
2016-03-17 11:20:18.775 ThaliTest[1611:2583227] client session: reverseConnect
,2016-03-17 11:20:18.776 ThaliTest[1611:2583227] client session: stateChange:0->1 FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
,2016-03-17 11:20:20.224 ThaliTest[1611:2583013] multipeer session: reset timer
2016-03-17 11:20:20.225 ThaliTest[1611:2583013] server: rejecting invitation from FD1CC9F2-9667-4D2B-A114-31A3E1486EC6 due to previous generation (20B211DA-8CC3-44A8-A409-C300A,017DFDB:6 != 20B211DA-8CC3-44A8-A409-C300A017DFDB:5)
,2016-03-17 11:20:20.257 ThaliTest[1611:2583696] client session: not connected FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
2016-03-17 11:20:20.259 ThaliTest[1611:2583696] client session: onLinkFailure: FD1CC9F2-9667-4D2B-A114-31A3E1486EC6
2016-03-17 11:20:20.2,59 ThaliTest[1611:2583696] client session: disconnect
2016-03-17 11:20:20.260 ThaliTest[1611:2583696] client session: stateChange:1->0 FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
2016-03-17 11:20:20.260 ThaliTest[1611:2583696] client session: no connect callb,ack (server initiated)
,2016-03-17 11:20:23.346 ThaliTest[1611:2583013] multipeer session: reset timer
2016-03-17 11:20:23.347 ThaliTest[1611:2583013] server: disconnecting to refresh session (FD1CC9F2-9667-4D2B-A114-31A3E1486EC6)
2016-03-17 11:20:23.347 ThaliTest[1611:2583013], server: rejecting invitation from FD1CC9F2-9667-4D2B-A114-31A3E1486EC6 due to previous generation (20B211DA-8CC3-44A8-A409-C300A017DFDB:6 != 20B211DA-8CC3-44A8-A409-C300A017DFDB:5)
,2016-03-17 11:20:26.511 ThaliTest[1611:2583013] multipeer session: reset timer
2016-03-17 11:20:26.511 ThaliTest[1611:2583013] server: disconnecting to refresh session (FD1CC9F2-9667-4D2B-A114-31A3E1486EC6)
2016-03-17 11:20:26.512 ThaliTest[1611:2583013], server: rejecting invitation from FD1CC9F2-9667-4D2B-A114-31A3E1486EC6 due to previous generation (20B211DA-8CC3-44A8-A409-C300A017DFDB:6 != 20B211DA-8CC3-44A8-A409-C300A017DFDB:5)
,2016-03-17 11:20:28.777 ThaliTest[1611:2583013] jxcore: connect: fail: Timed out awaiting reverse connection
INFO testThaliMobileNative Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative Scheduling a connect retry - retries left: 9
,2016-03-17 11:20:29.581 ThaliTest[1611:2583013] multipeer session: reset timer
,2016-03-17 11:20:29.582 ThaliTest[1611:2583013] server: disconnecting to refresh session (FD1CC9F2-9667-4D2B-A114-31A3E1486EC6)
,2016-03-17 11:20:29.582 ThaliTest[1611:2583013] server: rejecting invitation from FD1CC9F2-9667-4D2B-A114-31A3E1486EC6 due to previous generation (20B211DA-8CC3-44A8-A409-C300A017DFDB:6 != 20B211DA-8CC3-44A8-A409-C300A017DFDB:5)
,2016-03-17 11:20:31.796 ThaliTest[1611:2583227] jxcore: connect FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
2016-03-17 11:20:31.797 ThaliTest[1611:2583227] client: server will connect
2016-03-17 11:20:31.797 ThaliTest[1611:2583227] client session: reverseConn,ect
2016-03-17 11:20:31.797 ThaliTest[1611:2583227] client session: stateChange:0->1 FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
,2016-03-17 11:20:32.245 ThaliTest[1611:2583606] client session: not connected FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
2016-03-17 11:20:32.246 ThaliTest[1611:2583606] client session: onLinkFailure: FD1CC9F2-9667-4D2B-A114-31A3E1486EC6
,2016-03-17 11:20:32.246 ThaliTest[1611:2583606] client session: disconnect
,2016-03-17 11:20:32.248 ThaliTest[1611:2583606] client session: stateChange:1->0 FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
2016-03-17 11:20:32.249 ThaliTest[1611:2583606] client session: no connect callback (server initiated)
,2016-03-17 11:20:32.668 ThaliTest[1611:2583013] multipeer session: reset timer
2016-03-17 11:20:32.668 ThaliTest[1611:2583013] server: disconnecting to refresh session (FD1CC9F2-9667-4D2B-A114-31A3E1486EC6)
2016-03-17 11:20:32.669 ThaliTest[1611:2583013], server: rejecting invitation from FD1CC9F2-9667-4D2B-A114-31A3E1486EC6 due to previous generation (20B211DA-8CC3-44A8-A409-C300A017DFDB:6 != 20B211DA-8CC3-44A8-A409-C300A017DFDB:5)
,2016-03-17 11:20:35.919 ThaliTest[1611:2583013] multipeer session: reset timer
2016-03-17 11:20:35.920 ThaliTest[1611:2583013] server: disconnecting to refresh session (FD1CC9F2-9667-4D2B-A114-31A3E1486EC6)
2016-03-17 11:20:35.920 ThaliTest[1611:2583013], server: rejecting invitation from FD1CC9F2-9667-4D2B-A114-31A3E1486EC6 due to previous generation (20B211DA-8CC3-44A8-A409-C300A017DFDB:6 != 20B211DA-8CC3-44A8-A409-C300A017DFDB:5)
,2016-03-17 11:20:38.013 ThaliTest[1611:2583013] multipeer manager: restart client
,2016-03-17 11:20:38.031 ThaliTest[1611:2583013] client: found existing peer: FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
,2016-03-17 11:20:39.063 ThaliTest[1611:2583013] multipeer session: reset timer
2016-03-17 11:20:39.063 ThaliTest[1611:2583013] server: disconnecting to refresh session (FD1CC9F2-9667-4D2B-A114-31A3E1486EC6)
2016-03-17 11:20:39.063 ThaliTest[1611:2583013], server: rejecting invitation from FD1CC9F2-9667-4D2B-A114-31A3E1486EC6 due to previous generation (20B211DA-8CC3-44A8-A409-C300A017DFDB:6 != 20B211DA-8CC3-44A8-A409-C300A017DFDB:5)
,2016-03-17 11:20:41.799 ThaliTest[1611:2583013] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative Scheduling a connect retry - retries left: 8
,2016-03-17 11:20:42.176 ThaliTest[1611:2583013] multipeer session: reset timer
2016-03-17 11:20:42.177 ThaliTest[1611:2583013] server: disconnecting to refresh session (FD1CC9F2-9667-4D2B-A114-31A3E1486EC6)
2016-03-17 11:20:42.177 ThaliTest[1611:2583013], server: rejecting invitation from FD1CC9F2-9667-4D2B-A114-31A3E1486EC6 due to previous generation (20B211DA-8CC3-44A8-A409-C300A017DFDB:6 != 20B211DA-8CC3-44A8-A409-C300A017DFDB:5)
,2016-03-17 11:20:44.811 ThaliTest[1611:2583227] jxcore: connect FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
2016-03-17 11:20:44.812 ThaliTest[1611:2583227] client: server will connect
2016-03-17 11:20:44.812 ThaliTest[1611:2583227] client session: reverseConn,ect
2016-03-17 11:20:44.813 ThaliTest[1611:2583227] client session: stateChange:0->1 FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
,2016-03-17 11:20:45.358 ThaliTest[1611:2583013] multipeer session: reset timer
2016-03-17 11:20:45.359 ThaliTest[1611:2583013] server: disconnecting to refresh session (FD1CC9F2-9667-4D2B-A114-31A3E1486EC6)
,2016-03-17 11:20:45.360 ThaliTest[1611:2583013] server: rejecting invitation from FD1CC9F2-9667-4D2B-A114-31A3E1486EC6 due to previous generation (20B211DA-8CC3-44A8-A409-C300A017DFDB:6 != 20B211DA-8CC3-44A8-A409-C300A017DFDB:5)
,2016-03-17 11:20:45.383 ThaliTest[1611:2583606] client session: not connected FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
2016-03-17 11:20:45.384 ThaliTest[1611:2583606] client session: onLinkFailure: FD1CC9F2-9667-4D2B-A114-31A3E1486EC6
2016-03-17 11:20:45.3,84 ThaliTest[1611:2583606] client session: disconnect
2016-03-17 11:20:45.385 ThaliTest[1611:2583606] client session: stateChange:1->0 FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
2016-03-17 11:20:45.386 ThaliTest[1611:2583606] client session: no connect callb,ack (server initiated)
,2016-03-17 11:20:48.470 ThaliTest[1611:2583013] multipeer session: reset timer
2016-03-17 11:20:48.470 ThaliTest[1611:2583013] server: disconnecting to refresh session (FD1CC9F2-9667-4D2B-A114-31A3E1486EC6)
2016-03-17 11:20:48.471 ThaliTest[1611:2583013], server: rejecting invitation from FD1CC9F2-9667-4D2B-A114-31A3E1486EC6 due to previous generation (20B211DA-8CC3-44A8-A409-C300A017DFDB:6 != 20B211DA-8CC3-44A8-A409-C300A017DFDB:5)
,2016-03-17 11:20:54.814 ThaliTest[1611:2583013] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative Scheduling a connect retry - retries left: 7
,2016-03-17 11:20:57.820 ThaliTest[1611:2583227] jxcore: connect FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
2016-03-17 11:20:57.820 ThaliTest[1611:2583227] client: server will connect
2016-03-17 11:20:57.821 ThaliTest[1611:2583227] client session: reverseConnect
2016-03-17 11:20:57.821 ThaliTest[1611:2583227] client session: stateChange:0->1 FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
,2016-03-17 11:20:58.014 ThaliTest[1611:2583013] multipeer manager: restart client
,2016-03-17 11:20:58.036 ThaliTest[1611:2583013] client: found existing peer: FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
,2016-03-17 11:21:07.822 ThaliTest[1611:2583013] jxcore: connect: fail: Timed out awaiting reverse connection
,INFO testThaliMobileNative Connect returned an error: Timed out awaiting reverse connection
,INFO testThaliMobileNative Scheduling a connect retry - retries left: 6
,2016-03-17 11:21:10.838 ThaliTest[1611:2583227] jxcore: connect FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
2016-03-17 11:21:10.839 ThaliTest[1611:2583227] client: already connect(ing/ed) to FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
2016-03-17 11:21:10.840 Thali,Test[1611:2583227] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative Connect returned an error: Already connect(ing/ed)
,INFO testThaliMobileNative Scheduling a connect retry - retries left: 5
,2016-03-17 11:21:13.854 ThaliTest[1611:2583227] jxcore: connect FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
2016-03-17 11:21:13.855 ThaliTest[1611:2583227] client: already connect(ing/ed) to FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
2016-03-17 11:21:13.855 ThaliTest[1611:2583227] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative Connect returned an error: Already connect(ing/ed)
,INFO testThaliMobileNative Scheduling a connect retry - retries left: 4
,2016-03-17 11:21:16.872 ThaliTest[1611:2583227] jxcore: connect FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
2016-03-17 11:21:16.873 ThaliTest[1611:2583227] client: already connect(ing/ed) to FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
2016-03-17 11:21:16.873 ThaliTest[1611:2583227] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative Connect returned an error: Already connect(ing/ed)
,INFO testThaliMobileNative Scheduling a connect retry - retries left: 3
,2016-03-17 11:21:18.014 ThaliTest[1611:2583013] multipeer manager: restart client
,2016-03-17 11:21:18.031 ThaliTest[1611:2583013] client: found existing peer: FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
,2016-03-17 11:21:19.890 ThaliTest[1611:2583227] jxcore: connect FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
2016-03-17 11:21:19.891 ThaliTest[1611:2583227] client: already connect(ing/ed) to FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
2016-03-17 11:21:19.892 Thali,Test[1611:2583227] jxcore: connect: fail: Already connect(ing/ed)
,INFO testThaliMobileNative Connect returned an error: Already connect(ing/ed)
,INFO testThaliMobileNative Scheduling a connect retry - retries left: 2
,2016-03-17 11:21:22.911 ThaliTest[1611:2583227] jxcore: connect FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
2016-03-17 11:21:22.911 ThaliTest[1611:2583227] client: already connect(ing/ed) to FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
2016-03-17 11:21:22.912 Thali,Test[1611:2583227] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative Connect returned an error: Already connect(ing/ed)
,INFO testThaliMobileNative Scheduling a connect retry - retries left: 1
,2016-03-17 11:21:25.925 ThaliTest[1611:2583227] jxcore: connect FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
2016-03-17 11:21:25.926 ThaliTest[1611:2583227] client: already connect(ing/ed) to FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
2016-03-17 11:21:25.926 Thali,Test[1611:2583227] jxcore: connect: fail: Already connect(ing/ed)
INFO testThaliMobileNative Connect returned an error: Already connect(ing/ed)
WARN testThaliMobileNative Too many connect retries!
,2016-03-17 11:21:30.805 ThaliTest[1611:2583816] client session: not connected FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
2016-03-17 11:21:30.805 ThaliTest[1611:2583816] client session: onLinkFailure: FD1CC9F2-9667-4D2B-A114-31A3E1486EC6
2016-03-17 11:21:30.8,05 ThaliTest[1611:2583816] client session: disconnect
2016-03-17 11:21:30.806 ThaliTest[1611:2583816] client session: stateChange:1->0 FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
2016-03-17 11:21:30.806 ThaliTest[1611:2583816] client session: no connect callback (server initiated)
,2016-03-17 11:21:38.014 ThaliTest[1611:2583013] multipeer manager: restart client
,2016-03-17 11:21:38.033 ThaliTest[1611:2583013] client: found existing peer: FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
,2016-03-17 11:21:58.014 ThaliTest[1611:2583013] multipeer manager: restart client
,2016-03-17 11:21:58.031 ThaliTest[1611:2583013] client: found existing peer: FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
,2016-03-17 11:22:18.014 ThaliTest[1611:2583013] multipeer manager: restart client
,2016-03-17 11:22:18.031 ThaliTest[1611:2583013] client: found existing peer: FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
,2016-03-17 11:22:38.014 ThaliTest[1611:2583013] multipeer manager: restart client
,2016-03-17 11:22:38.030 ThaliTest[1611:2583013] client: found existing peer: FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
,2016-03-17 11:22:58.014 ThaliTest[1611:2583013] multipeer manager: restart client
,2016-03-17 11:22:58.030 ThaliTest[1611:2583013] client: found existing peer: FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
,2016-03-17 11:23:18.014 ThaliTest[1611:2583013] multipeer manager: restart client
,2016-03-17 11:23:18.031 ThaliTest[1611:2583013] client: found existing peer: FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
,2016-03-17 11:23:38.014 ThaliTest[1611:2583013] multipeer manager: restart client
,2016-03-17 11:23:38.030 ThaliTest[1611:2583013] client: found existing peer: FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
,2016-03-17 11:23:58.014 ThaliTest[1611:2583013] multipeer manager: restart client
,2016-03-17 11:23:58.032 ThaliTest[1611:2583013] client: found existing peer: FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
,2016-03-17 11:24:18.014 ThaliTest[1611:2583013] multipeer manager: restart client
,2016-03-17 11:24:18.033 ThaliTest[1611:2583013] client: found existing peer: FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
,2016-03-17 11:24:38.014 ThaliTest[1611:2583013] multipeer manager: restart client
,2016-03-17 11:24:38.031 ThaliTest[1611:2583013] client: found existing peer: FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
,2016-03-17 11:24:58.014 ThaliTest[1611:2583013] multipeer manager: restart client
,2016-03-17 11:24:58.031 ThaliTest[1611:2583013] client: found updated peer: FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:6
,2016-03-17 11:25:18.014 ThaliTest[1611:2583013] multipeer manager: restart client
,2016-03-17 11:25:18.031 ThaliTest[1611:2583013] client: found updated peer: FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
,2016-03-17 11:25:38.014 ThaliTest[1611:2583013] multipeer manager: restart client
,2016-03-17 11:25:38.029 ThaliTest[1611:2583013] client: found existing peer: FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
,2016-03-17 11:25:58.013 ThaliTest[1611:2583013] multipeer manager: restart client
,2016-03-17 11:25:58.032 ThaliTest[1611:2583013] client: found existing peer: FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
,2016-03-17 11:26:18.014 ThaliTest[1611:2583013] multipeer manager: restart client
,2016-03-17 11:26:18.033 ThaliTest[1611:2583013] client: found existing peer: FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
,2016-03-17 11:26:38.013 ThaliTest[1611:2583013] multipeer manager: restart client
,2016-03-17 11:26:38.035 ThaliTest[1611:2583013] client: found existing peer: FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
,2016-03-17 11:26:58.014 ThaliTest[1611:2583013] multipeer manager: restart client
,2016-03-17 11:26:58.032 ThaliTest[1611:2583013] client: found existing peer: FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
,2016-03-17 11:27:18.013 ThaliTest[1611:2583013] multipeer manager: restart client
,2016-03-17 11:27:18.029 ThaliTest[1611:2583013] client: found existing peer: FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
,2016-03-17 11:27:38.013 ThaliTest[1611:2583013] multipeer manager: restart client
,2016-03-17 11:27:38.030 ThaliTest[1611:2583013] client: found updated peer: FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:6
,2016-03-17 11:27:58.014 ThaliTest[1611:2583013] multipeer manager: restart client
,2016-03-17 11:27:58.032 ThaliTest[1611:2583013] client: found updated peer: FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
,2016-03-17 11:28:18.014 ThaliTest[1611:2583013] multipeer manager: restart client
,2016-03-17 11:28:18.030 ThaliTest[1611:2583013] client: found existing peer: FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
,2016-03-17 11:28:38.014 ThaliTest[1611:2583013] multipeer manager: restart client
,2016-03-17 11:28:38.030 ThaliTest[1611:2583013] client: found existing peer: FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
,2016-03-17 11:28:58.014 ThaliTest[1611:2583013] multipeer manager: restart client
,2016-03-17 11:28:58.032 ThaliTest[1611:2583013] client: found existing peer: FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
,2016-03-17 11:29:18.014 ThaliTest[1611:2583013] multipeer manager: restart client
,2016-03-17 11:29:18.032 ThaliTest[1611:2583013] client: found existing peer: FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
,2016-03-17 11:29:38.014 ThaliTest[1611:2583013] multipeer manager: restart client
,2016-03-17 11:29:38.030 ThaliTest[1611:2583013] client: found existing peer: FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
,2016-03-17 11:29:58.014 ThaliTest[1611:2583013] multipeer manager: restart client
,2016-03-17 11:29:58.032 ThaliTest[1611:2583013] client: found existing peer: FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
,2016-03-17 11:30:18.014 ThaliTest[1611:2583013] multipeer manager: restart client
,2016-03-17 11:30:18.033 ThaliTest[1611:2583013] client: found existing peer: FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
,2016-03-17 11:30:38.013 ThaliTest[1611:2583013] multipeer manager: restart client
,2016-03-17 11:30:38.031 ThaliTest[1611:2583013] client: found existing peer: FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
,2016-03-17 11:30:58.014 ThaliTest[1611:2583013] multipeer manager: restart client
,2016-03-17 11:30:58.030 ThaliTest[1611:2583013] client: found existing peer: FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
,2016-03-17 11:31:18.014 ThaliTest[1611:2583013] multipeer manager: restart client
,2016-03-17 11:31:38.014 ThaliTest[1611:2583013] multipeer manager: restart client
,2016-03-17 11:31:38.025 ThaliTest[1611:2583013] client: found existing peer: FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
,2016-03-17 11:31:58.014 ThaliTest[1611:2583013] multipeer manager: restart client
,2016-03-17 11:31:58.025 ThaliTest[1611:2583013] client: found existing peer: FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
,2016-03-17 11:32:18.014 ThaliTest[1611:2583013] multipeer manager: restart client
,2016-03-17 11:32:18.025 ThaliTest[1611:2583013] client: found existing peer: FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
,2016-03-17 11:32:38.014 ThaliTest[1611:2583013] multipeer manager: restart client
,2016-03-17 11:32:38.026 ThaliTest[1611:2583013] client: found existing peer: FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
,2016-03-17 11:32:58.014 ThaliTest[1611:2583013] multipeer manager: restart client
,2016-03-17 11:32:58.026 ThaliTest[1611:2583013] client: found existing peer: FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
,2016-03-17 11:33:18.014 ThaliTest[1611:2583013] multipeer manager: restart client
,2016-03-17 11:33:18.025 ThaliTest[1611:2583013] client: found existing peer: FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
,2016-03-17 11:33:38.014 ThaliTest[1611:2583013] multipeer manager: restart client
,2016-03-17 11:33:38.026 ThaliTest[1611:2583013] client: found existing peer: FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
,2016-03-17 11:33:58.014 ThaliTest[1611:2583013] multipeer manager: restart client
,2016-03-17 11:33:58.025 ThaliTest[1611:2583013] client: found existing peer: FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
,2016-03-17 11:34:18.014 ThaliTest[1611:2583013] multipeer manager: restart client
,2016-03-17 11:34:18.025 ThaliTest[1611:2583013] client: found existing peer: FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
,2016-03-17 11:34:38.014 ThaliTest[1611:2583013] multipeer manager: restart client
,2016-03-17 11:34:38.027 ThaliTest[1611:2583013] client: found existing peer: FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
,2016-03-17 11:34:58.013 ThaliTest[1611:2583013] multipeer manager: restart client
,2016-03-17 11:34:58.026 ThaliTest[1611:2583013] client: found existing peer: FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
,2016-03-17 11:35:18.013 ThaliTest[1611:2583013] multipeer manager: restart client
,2016-03-17 11:35:18.027 ThaliTest[1611:2583013] client: found existing peer: FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
,2016-03-17 11:35:38.014 ThaliTest[1611:2583013] multipeer manager: restart client
,2016-03-17 11:35:38.025 ThaliTest[1611:2583013] client: found existing peer: FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
,2016-03-17 11:35:58.014 ThaliTest[1611:2583013] multipeer manager: restart client
,2016-03-17 11:35:58.027 ThaliTest[1611:2583013] client: found existing peer: FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
,2016-03-17 11:36:18.014 ThaliTest[1611:2583013] multipeer manager: restart client
,2016-03-17 11:36:18.026 ThaliTest[1611:2583013] client: found existing peer: FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
,2016-03-17 11:36:38.014 ThaliTest[1611:2583013] multipeer manager: restart client
,2016-03-17 11:36:38.025 ThaliTest[1611:2583013] client: found updated peer: FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:6
,2016-03-17 11:36:58.014 ThaliTest[1611:2583013] multipeer manager: restart client
,2016-03-17 11:36:58.026 ThaliTest[1611:2583013] client: found updated peer: FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
,2016-03-17 11:37:18.014 ThaliTest[1611:2583013] multipeer manager: restart client
,2016-03-17 11:37:18.026 ThaliTest[1611:2583013] client: found existing peer: FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
,2016-03-17 11:37:38.014 ThaliTest[1611:2583013] multipeer manager: restart client
,2016-03-17 11:37:38.026 ThaliTest[1611:2583013] client: found existing peer: FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
,2016-03-17 11:37:58.014 ThaliTest[1611:2583013] multipeer manager: restart client
,2016-03-17 11:37:58.026 ThaliTest[1611:2583013] client: found existing peer: FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5
,2016-03-17 11:38:18.014 ThaliTest[1611:2583013] multipeer manager: restart client
,2016-03-17 11:38:18.027 ThaliTest[1611:2583013] client: found existing peer: FD1CC9F2-9667-4D2B-A114-31A3E1486EC6:5

```
