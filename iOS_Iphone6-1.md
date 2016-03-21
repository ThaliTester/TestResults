#### Test 635253937ae73fc_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/635253937ae73fc/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/D143E9F2-D204-4F41-97B4-69C7BCF57745/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/D143E9F2-D204-4F41-97B4-69C7BCF57745/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/635253937ae73fc/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/635253937ae73fc/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/DE0CB8E0-1534-439A-B4BD-153EE135996E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53634"
,(lldb)     command script import "/tmp/D143E9F2-D204-4F41-97B4-69C7BCF57745/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-21 08:35:29.901 ThaliTest[1860:3157563] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B006A99D-0E4F-4DB9-B13A-432216F78E4E/Library/Cookies/Cookies.binarycookies
,2016-03-21 08:35:30.242 ThaliTest[1860:3157563] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-21 08:35:30.244 ThaliTest[1860:3157563] Multi-tasking -> Device: YES, App: YES
,2016-03-21 08:35:30.266 ThaliTest[1860:3157563] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-21 08:35:32.115 ThaliTest[1860:3157563] Using UIWebView
,2016-03-21 08:35:32.121 ThaliTest[1860:3157563] [CDVTimer][handleopenurl] 0.383019ms
,2016-03-21 08:35:32.129 ThaliTest[1860:3157563] [CDVTimer][intentandnavigationfilter] 7.339001ms
2016-03-21 08:35:32.130 ThaliTest[1860:3157563] [CDVTimer][gesturehandler] 0.319958ms
2016-03-21 08:35:32.131 ThaliTest[1860:3157563] [CDVTimer][TotalPluginStartup] 9.797037ms
,2016-03-21 08:35:39.176 ThaliTest[1860:3157563] Resetting plugins due to page load.
,2016-03-21 08:35:42.498 ThaliTest[1860:3157563] Finished load of: file:///var/mobile/Containers/Bundle/Application/DE0CB8E0-1534-439A-B4BD-153EE135996E/ThaliTest.app/www/index.html
,2016-03-21 08:35:42.712 ThaliTest[1860:3157563] JXcore Cordova plugin initializing
,2016-03-21 08:35:42.818 ThaliTest[1860:3157757] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-21 08:35:47.066 ThaliTest[1860:3157757] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-21 08:35:47.066 ThaliTest[1860:3157757] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-21 08:35:47.067 ThaliTest[1860:3157757] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-21 08:35:47.070 ThaliTest[1860:3157757] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-Iphone6-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DE0CB8E0-1534-439A-B4BD-153EE135996E/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DE0CB8E0-1534-439A-B4BD-153EE135996E/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DE0CB8E0-1534-439A-B4BD-153EE135996E/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DE0CB8E0-1534-439A-B4BD-153EE135996E/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DE0CB8E0-1534-439A-B4BD-153EE135996E/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DE0CB8E0-1534-439A-B4BD-153EE135996E/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DE0CB8E0-1534-439A-B4BD-153EE135996E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DE0CB8E0-1534-439A-B4BD-153EE135996E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DE0CB8E0-1534-439A-B4BD-153EE135996E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DE0CB8E0-1534-439A-B4BD-153EE135996E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DE0CB8E0-1534-439A-B4BD-153EE135996E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DE0CB8E0-1534-439A-B4BD-153EE135996E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DE0CB8E0-1534-439A-B4BD-153EE135996E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DE0CB8E0-1534-439A-B4BD-153EE135996E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DE0CB8E0-1534-439A-B4BD-153EE135996E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DE0CB8E0-1534-439A-B4BD-153EE135996E/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DE0CB8E0-1534-439A-B4BD-153EE135996E/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DE0CB8E0-1534-439A-B4BD-153EE135996E/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DE0CB8E0-1534-439A-B4BD-153EE135996E/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/DE0CB8E0-1534-439A-B4BD-153EE135996E/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-21 08:35:55.871 ThaliTest[1860:3157563] THREAD WARNING: ['JXcore'] took '6309.133057' ms. Plugin should use a background thread.
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
,2016-03-21 08:39:16.895 ThaliTest[1860:3157757] jxcore: startListeningForAdvertisements
,2016-03-21 08:39:16.898 ThaliTest[1860:3157757] multipeer manager: start client restart timer: 0x16d41fa0
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-21 08:39:16.901 ThaliTest[1860:3157757] jxcore: startListeningForAdvertisements: success
ok 129 Can call startListeningForAdvertisements without error
,2016-03-21 08:39:16.903 ThaliTest[1860:3157757] jxcore: stopListeningForAdvertisements
,2016-03-21 08:39:16.910 ThaliTest[1860:3157757] multipeer manager: stop client timer
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-21 08:39:16.913 ThaliTest[1860:3157757] jxcore: stopListeningForAdvertisements: success
,ok 130 Can call stopListeningForAdvertisements without error
,# setup
,2016-03-21 08:39:17.330 ThaliTest[1860:3157757] jxcore: stopListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-21 08:39:17.333 ThaliTest[1860:3157757] jxcore: stopListeningForAdvertisements: success
,ok 131 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-21 08:39:17.337 ThaliTest[1860:3157757] jxcore: stopAdvertisingAndListening
2016-03-21 08:39:17.337 ThaliTest[1860:3157757] THEMultipeerManager stopping peer
2016-03-21 08:39:17.337 ThaliTest[1860:3157757] jxcore: stopAdvertisingAndListening: suc,cess
ok 132 Should be able to call stopAdvertisingAndListening in teardown
,# 33. Calling startListeningForAdvertisements twice is NOT an error
,# teardown
,2016-03-21 08:39:17.883 ThaliTest[1860:3157757] jxcore: startListeningForAdvertisements
2016-03-21 08:39:17.884 ThaliTest[1860:3157757] multipeer manager: start client restart timer: 0x16d41fa0
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-21 08:39:17.886 ThaliTest[1860:3157757] jxcore: startListeningForAdvertisements: success
,ok 133 Can call startListeningForAdvertisements without error
2016-03-21 08:39:17.890 ThaliTest[1860:3157757] jxcore: startListeningForAdvertisements
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-21 08:39:17.892 ThaliTest[1860:3157757] jxcore: startListeningForAdvertisements: success
,ok 134 Can call startListeningForAdvertisements twice without error
,# setup
,2016-03-21 08:39:19.315 ThaliTest[1860:3157757] jxcore: stopListeningForAdvertisements
2016-03-21 08:39:19.316 ThaliTest[1860:3157757] multipeer manager: stop client timer
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-21 08:39:19.318 ThaliTest[1860:3157757] jxcore: stopListeningForAdvertisements: success
ok 135 Should be able to call stopListeningForAdvertisments in teardown
2016-03-21 08:39:19.321 ThaliTest[1860:3157757] jxcore: stopAdvertisingAndListening
2,016-03-21 08:39:19.322 ThaliTest[1860:3157757] THEMultipeerManager stopping peer
2016-03-21 08:39:19.322 ThaliTest[1860:3157757] jxcore: stopAdvertisingAndListening: success
ok 136 Should be able to call stopAdvertisingAndListening in teardown
,# 34. Can call start/stopUpdateAdvertisingAndListening
,# teardown
,2016-03-21 08:39:19.752 ThaliTest[1860:3157757] jxcore: startUpdateAdvertisingAndListening
2016-03-21 08:39:19.753 ThaliTest[1860:3157757] server: starting 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:1
2016-03-21 08:39:19.754 ThaliTest[1860:3157757] multipeer m,anager: start client restart timer: 0x16d41fa0
2016-03-21 08:39:19.754 ThaliTest[1860:3157757] THEMultipeerManager initialized peer 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:1
2016-03-21 08:39:19.754 ThaliTest[1860:3157757] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 137 Can call startUpdateAdvertisingAndListening without error
2016-03-21 08:39:19.757 ThaliTest[1860:3157757] jxcore: stopAdvertisingAndListening
2016-03-21 08:39:19.757 ThaliTest[1860:3157757] THEMultipeerManager stopping peer
,2016-03-21 08:39:19.762 ThaliTest[1860:3157757] multipeer manager: stop client timer
2016-03-21 08:39:19.763 ThaliTest[1860:3157757] jxcore: stopAdvertisingAndListening: success
ok 138 Can call stopAdvertisingAndListening without error
,# setup
,2016-03-21 08:39:20.229 ThaliTest[1860:3157757] jxcore: stopListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-21 08:39:20.231 ThaliTest[1860:3157757] jxcore: stopListeningForAdvertisements: success
,ok 139 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-21 08:39:20.234 ThaliTest[1860:3157757] jxcore: stopAdvertisingAndListening
,2016-03-21 08:39:20.235 ThaliTest[1860:3157757] THEMultipeerManager stopping peer
2016-03-21 08:39:20.236 ThaliTest[1860:3157757] jxcore: stopAdvertisingAndListening: success
ok 140 Should be able to call stopAdvertisingAndListening in teardown
,# 35. Calling startUpdateAdvertisingAndListening twice is NOT an error
,# teardown
,2016-03-21 08:39:21.277 ThaliTest[1860:3157757] jxcore: startUpdateAdvertisingAndListening
2016-03-21 08:39:21.278 ThaliTest[1860:3157757] server: starting 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:2
2016-03-21 08:39:21.279 ThaliTest[1860:3157757] multipeer m,anager: start client restart timer: 0x16d41fa0
2016-03-21 08:39:21.279 ThaliTest[1860:3157757] THEMultipeerManager initialized peer 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:2
2016-03-21 08:39:21.279 ThaliTest[1860:3157757] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 141 Can call startUpdateAdvertisingAndListening without error
,2016-03-21 08:39:21.282 ThaliTest[1860:3157757] jxcore: startUpdateAdvertisingAndListening
2016-03-21 08:39:21.285 ThaliTest[1860:3157757] THEMultipeerManager stopping peer
2016-03-21 08:39:21.286 ThaliTest[1860:3157757] multipeer manager: stop client ti,mer
2016-03-21 08:39:21.286 ThaliTest[1860:3157757] server: starting 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:3
2016-03-21 08:39:21.287 ThaliTest[1860:3157757] multipeer manager: start client restart timer: 0x16d41fa0
2016-03-21 08:39:21.287 ThaliTest[1860:,3157757] THEMultipeerManager initialized peer 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:3
2016-03-21 08:39:21.288 ThaliTest[1860:3157757] jxcore: startUpdateAdvertisingAndListening: success
ok 142 Can call startUpdateAdvertisingAndListening twice without erro,r
# setup
,2016-03-21 08:39:21.454 ThaliTest[1860:3157757] jxcore: stopListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-21 08:39:21.456 ThaliTest[1860:3157757] jxcore: stopListeningForAdvertisements: success
,ok 143 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-21 08:39:21.459 ThaliTest[1860:3157757] jxcore: stopAdvertisingAndListening
2016-03-21 08:39:21.459 ThaliTest[1860:3157757] THEMultipeerManager stopping peer
2016-03-21 08:39:21.460 ThaliTest[1860:3157757] multipeer manager: stop client timer
20,16-03-21 08:39:21.460 ThaliTest[1860:3157757] jxcore: stopAdvertisingAndListening: success
ok 144 Should be able to call stopAdvertisingAndListening in teardown
,# 36. peerAvailabilityChange is called
,# teardown
,2016-03-21 08:39:21.940 ThaliTest[1860:3157757] jxcore: startUpdateAdvertisingAndListening
2016-03-21 08:39:21.940 ThaliTest[1860:3157757] server: starting 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:4
2016-03-21 08:39:21.941 ThaliTest[1860:3157757] multipeer m,anager: start client restart timer: 0x16d41fa0
2016-03-21 08:39:21.942 ThaliTest[1860:3157757] THEMultipeerManager initialized peer 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:4
2016-03-21 08:39:21.942 ThaliTest[1860:3157757] jxcore: startUpdateAdvertisingAndListening: success
ok 145 Can call startUpdateAdvertisingAndListeningwithout error
,2016-03-21 08:39:21.945 ThaliTest[1860:3157757] jxcore: startListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-21 08:39:21.948 ThaliTest[1860:3157757] jxcore: startListeningForAdvertisements: success
ok 146 Can call startListeningForAdvertisements without error
,2016-03-21 08:39:23.876 ThaliTest[1860:3157563] client: found new peer: 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:4
,ok 147 peers must be an array
ok 148 peers must not be zero-length
ok 149 peer must have peerIdentifier
,ok 150 peerIdentifier must be a string
,ok 151 peer must have peerAvailable
,ok 152 peer must have pleaseConnect
,# setup
,2016-03-21 08:39:24.019 ThaliTest[1860:3157757] jxcore: stopListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-21 08:39:24.022 ThaliTest[1860:3157757] jxcore: stopListeningForAdvertisements: success
,ok 153 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-21 08:39:24.025 ThaliTest[1860:3157757] jxcore: stopAdvertisingAndListening
,2016-03-21 08:39:24.026 ThaliTest[1860:3157757] THEMultipeerManager stopping peer
2016-03-21 08:39:24.026 ThaliTest[1860:3157757] multipeer manager: stop client timer
2016-03-21 08:39:24.027 ThaliTest[1860:3157757] jxcore: stopAdvertisingAndListening: success
ok 154 Should be able to call stopAdvertisingAndListening in teardown
,# 37. Can connect to a remote peer
,# teardown
,2016-03-21 08:39:24.547 ThaliTest[1860:3157757] jxcore: startUpdateAdvertisingAndListening
2016-03-21 08:39:24.548 ThaliTest[1860:3157757] server: starting 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:5
2016-03-21 08:39:24.548 ThaliTest[1860:3157757] multipeer m,anager: start client restart timer: 0x16d41fa0
2016-03-21 08:39:24.549 ThaliTest[1860:3157757] THEMultipeerManager initialized peer 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:5
2016-03-21 08:39:24.549 ThaliTest[1860:3157757] jxcore: startUpdateAdvertisingAndLi,stening: success
ok 155 Can call startUpdateAdvertisingAndListening without error
2016-03-21 08:39:24.551 ThaliTest[1860:3157757] jxcore: startListeningForAdvertisements
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingA,ctive":true,"discoveryActive":true}
2016-03-21 08:39:24.553 ThaliTest[1860:3157757] jxcore: startListeningForAdvertisements: success
ok 156 Can call startListeningForAdvertisements without error
,2016-03-21 08:39:25.464 ThaliTest[1860:3157563] multipeer session: reset timer
2016-03-21 08:39:25.465 ThaliTest[1860:3157563] server: rejecting invitation from 1A7399AB-2639-4E30-AE4B-9B6B5C31291B due to previous generation (7AE3ED20-28A5-49DE-832C-CB513D1E3D29:5 != 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:4)
,2016-03-21 08:39:25.492 ThaliTest[1860:3157563] client: found new peer: 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:4
,INFO testThaliMobileNative Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"1A7399AB-2639-4E30-AE4B-9B6B5C31291B:4","pleaseConnect":0}]
2016-03-21 08:39:25.498 ThaliTest[1860:3157757] jxcore: connect 1A7399AB-2639-4E30-AE,4B-9B6B5C31291B:4
2016-03-21 08:39:25.498 ThaliTest[1860:3157757] client session: connect
2016-03-21 08:39:25.499 ThaliTest[1860:3157757] client session: stateChange:0->1 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:4
,2016-03-21 08:39:25.923 ThaliTest[1860:3158436] client session: not connected 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:4
,2016-03-21 08:39:25.924 ThaliTest[1860:3158436] client session: onLinkFailure: 1A7399AB-2639-4E30-AE4B-9B6B5C31291B
2016-03-21 08:39:25.926 ThaliTest[1860:3158436] client session: disconnect
2016-03-21 08:39:25.926 ThaliTest[1860:3158436] client session:, stateChange:1->0 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:4
2016-03-21 08:39:25.927 ThaliTest[1860:3158436] client session: fireConnectCallback: 1A7399AB-2639-4E30-AE4B-9B6B5C31291B
2016-03-21 08:39:25.927 ThaliTest[1860:3158436] jxcore: connect: fail: Peer, disconnected
INFO testThaliMobileNative Connect returned an error: Peer disconnected
INFO testThaliMobileNative Scheduling a connect retry - retries left: 9
,2016-03-21 08:39:28.941 ThaliTest[1860:3157757] jxcore: connect 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:4
2016-03-21 08:39:28.941 ThaliTest[1860:3157757] client session: connect
2016-03-21 08:39:28.942 ThaliTest[1860:3157757] client session: stateChange:0->,1 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:4
,2016-03-21 08:39:29.058 ThaliTest[1860:3158435] client session: not connected 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:4
2016-03-21 08:39:29.059 ThaliTest[1860:3158435] client session: onLinkFailure: 1A7399AB-2639-4E30-AE4B-9B6B5C31291B
,2016-03-21 08:39:29.059 ThaliTest[1860:3158435] client session: disconnect
2016-03-21 08:39:29.061 ThaliTest[1860:3158435] client session: stateChange:1->0 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:4
2016-03-21 08:39:29.061 ThaliTest[1860:3158435] client sess,ion: fireConnectCallback: 1A7399AB-2639-4E30-AE4B-9B6B5C31291B
2016-03-21 08:39:29.062 ThaliTest[1860:3158435] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative Connect returned an error: Peer disconnected
INFO testThaliMobileNative Sc,heduling a connect retry - retries left: 8
,2016-03-21 08:39:32.077 ThaliTest[1860:3157757] jxcore: connect 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:4
2016-03-21 08:39:32.077 ThaliTest[1860:3157757] client session: connect
2016-03-21 08:39:32.078 ThaliTest[1860:3157757] client session: stateChange:0->,1 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:4
,2016-03-21 08:39:32.152 ThaliTest[1860:3158436] client session: not connected 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:4
,2016-03-21 08:39:32.153 ThaliTest[1860:3158436] client session: onLinkFailure: 1A7399AB-2639-4E30-AE4B-9B6B5C31291B
,2016-03-21 08:39:32.153 ThaliTest[1860:3158436] client session: disconnect
,2016-03-21 08:39:32.154 ThaliTest[1860:3158436] client session: stateChange:1->0 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:4
2016-03-21 08:39:32.155 ThaliTest[1860:3158436] client session: fireConnectCallback: 1A7399AB-2639-4E30-AE4B-9B6B5C31291B
2016-03-21 0,8:39:32.155 ThaliTest[1860:3158436] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative Connect returned an error: Peer disconnected
INFO testThaliMobileNative Scheduling a connect retry - retries left: 7
,2016-03-21 08:39:35.159 ThaliTest[1860:3157757] jxcore: connect 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:4
2016-03-21 08:39:35.159 ThaliTest[1860:3157757] client session: connect
2016-03-21 08:39:35.160 ThaliTest[1860:3157757] client session: stateChange:0->,1 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:4
,2016-03-21 08:39:36.186 ThaliTest[1860:3158438] client session: not connected 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:4
2016-03-21 08:39:36.186 ThaliTest[1860:3158438] client session: onLinkFailure: 1A7399AB-2639-4E30-AE4B-9B6B5C31291B
2016-03-21 08:39:36.187 ThaliTest[1860:3158438] client session: disconnect
,2016-03-21 08:39:36.187 ThaliTest[1860:3158438] client session: stateChange:1->0 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:4
,2016-03-21 08:39:36.190 ThaliTest[1860:3158438] client session: fireConnectCallback: 1A7399AB-2639-4E30-AE4B-9B6B5C31291B
,2016-03-21 08:39:36.190 ThaliTest[1860:3158438] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative Connect returned an error: Peer disconnected
INFO testThaliMobileNative Scheduling a connect retry - retries left: 6
,2016-03-21 08:39:38.441 ThaliTest[1860:3157563] multipeer session: reset timer
2016-03-21 08:39:38.442 ThaliTest[1860:3157563] server: disconnecting to refresh session (1A7399AB-2639-4E30-AE4B-9B6B5C31291B)
2016-03-21 08:39:38.442 ThaliTest[1860:3157563], server: rejecting invitation from 1A7399AB-2639-4E30-AE4B-9B6B5C31291B due to previous generation (7AE3ED20-28A5-49DE-832C-CB513D1E3D29:5 != 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:4)
,2016-03-21 08:39:39.196 ThaliTest[1860:3157757] jxcore: connect 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:4
2016-03-21 08:39:39.197 ThaliTest[1860:3157757] client session: connect
2016-03-21 08:39:39.198 ThaliTest[1860:3157757] client session: stateChange:0->1 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:4
,2016-03-21 08:39:40.335 ThaliTest[1860:3158437] client session: not connected 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:4
2016-03-21 08:39:40.336 ThaliTest[1860:3158437] client session: onLinkFailure: 1A7399AB-2639-4E30-AE4B-9B6B5C31291B
2016-03-21 08:39:40.3,36 ThaliTest[1860:3158437] client session: disconnect
,2016-03-21 08:39:40.337 ThaliTest[1860:3158437] client session: stateChange:1->0 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:4
2016-03-21 08:39:40.340 ThaliTest[1860:3158437] client session: fireConnectCallback: 1A7399AB-2639-4E30-AE4B-9B6B5C31291B
2016-03-21 0,8:39:40.340 ThaliTest[1860:3158437] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative Connect returned an error: Peer disconnected
INFO testThaliMobileNative Scheduling a connect retry - retries left: 5
,2016-03-21 08:39:43.344 ThaliTest[1860:3157757] jxcore: connect 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:4
2016-03-21 08:39:43.345 ThaliTest[1860:3157757] client session: connect
2016-03-21 08:39:43.345 ThaliTest[1860:3157757] client session: stateChange:0->,1 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:4
,2016-03-21 08:39:44.550 ThaliTest[1860:3157563] multipeer manager: restart client
,2016-03-21 08:39:44.566 ThaliTest[1860:3157563] client: found updated peer: 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:5
INFO testThaliMobileNative Received peerAvailabilityChanged with peers: [{"peerAvailable":1,"peerIdentifier":"1A7399AB-2639-4E30-AE4B-9B6B5C,31291B:5","pleaseConnect":0}]
,2016-03-21 08:39:51.548 ThaliTest[1860:3157563] multipeer session: reset timer
2016-03-21 08:39:51.548 ThaliTest[1860:3157563] server: disconnecting to refresh session (1A7399AB-2639-4E30-AE4B-9B6B5C31291B)
2016-03-21 08:39:51.549 ThaliTest[1860:3157563], server: rejecting invitation from 1A7399AB-2639-4E30-AE4B-9B6B5C31291B due to previous generation (7AE3ED20-28A5-49DE-832C-CB513D1E3D29:5 != 7AE3ED20-28A5-49DE-832C-CB513D1E3D29:4)
,2016-03-21 08:40:04.549 ThaliTest[1860:3157563] multipeer manager: restart client
,2016-03-21 08:40:04.566 ThaliTest[1860:3157563] client: found existing peer: 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:5
,2016-03-21 08:40:16.353 ThaliTest[1860:3158687] client session: not connected 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:5
2016-03-21 08:40:16.354 ThaliTest[1860:3158687] client session: onLinkFailure: 1A7399AB-2639-4E30-AE4B-9B6B5C31291B
2016-03-21 08:40:16.3,54 ThaliTest[1860:3158687] client session: disconnect
2016-03-21 08:40:16.354 ThaliTest[1860:3158687] client session: stateChange:1->0 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:5
2016-03-21 08:40:16.355 ThaliTest[1860:3158687] client session: fireConnectCallb,ack: 1A7399AB-2639-4E30-AE4B-9B6B5C31291B
2016-03-21 08:40:16.356 ThaliTest[1860:3158687] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative Connect returned an error: Peer disconnected
INFO testThaliMobileNative Scheduling a connect re,try - retries left: 4
,2016-03-21 08:40:19.371 ThaliTest[1860:3157757] jxcore: connect 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:4
2016-03-21 08:40:19.372 ThaliTest[1860:3157757] client session: connect
2016-03-21 08:40:19.372 ThaliTest[1860:3157757] client session: stateChange:0->,1 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:5
,2016-03-21 08:40:19.507 ThaliTest[1860:3158688] client session: not connected 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:5
,2016-03-21 08:40:19.509 ThaliTest[1860:3158688] client session: onLinkFailure: 1A7399AB-2639-4E30-AE4B-9B6B5C31291B
2016-03-21 08:40:19.509 ThaliTest[1860:3158688] client session: disconnect
2016-03-21 08:40:19.509 ThaliTest[1860:3158688] client session: stateChange:1->0 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:5
,2016-03-21 08:40:19.512 ThaliTest[1860:3158688] client session: fireConnectCallback: 1A7399AB-2639-4E30-AE4B-9B6B5C31291B
2016-03-21 08:40:19.512 ThaliTest[1860:3158688] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative Connect returned an error: Peer disconnected
,INFO testThaliMobileNative Scheduling a connect retry - retries left: 3
,2016-03-21 08:40:22.520 ThaliTest[1860:3157757] jxcore: connect 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:4
2016-03-21 08:40:22.521 ThaliTest[1860:3157757] client session: connect
2016-03-21 08:40:22.521 ThaliTest[1860:3157757] client session: stateChange:0->1 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:5
,2016-03-21 08:40:23.050 ThaliTest[1860:3158687] client session: not connected 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:5
2016-03-21 08:40:23.051 ThaliTest[1860:3158687] client session: onLinkFailure: 1A7399AB-2639-4E30-AE4B-9B6B5C31291B
2016-03-21 08:40:23.051 ThaliTest[1860:3158687] client session: disconnect
,2016-03-21 08:40:23.051 ThaliTest[1860:3158687] client session: stateChange:1->0 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:5
2016-03-21 08:40:23.055 ThaliTest[1860:3158687] client session: fireConnectCallback: 1A7399AB-2639-4E30-AE4B-9B6B5C31291B
2016-03-21 0,8:40:23.055 ThaliTest[1860:3158687] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative Connect returned an error: Peer disconnected
INFO testThaliMobileNative Scheduling a connect retry - retries left: 2
,2016-03-21 08:40:24.550 ThaliTest[1860:3157563] multipeer manager: restart client
,2016-03-21 08:40:24.567 ThaliTest[1860:3157563] client: found existing peer: 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:5
,2016-03-21 08:40:26.070 ThaliTest[1860:3157757] jxcore: connect 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:4
2016-03-21 08:40:26.071 ThaliTest[1860:3157757] client session: connect
2016-03-21 08:40:26.071 ThaliTest[1860:3157757] client session: stateChange:0->1 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:5
,2016-03-21 08:40:26.179 ThaliTest[1860:3158792] client session: not connected 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:5
2016-03-21 08:40:26.180 ThaliTest[1860:3158792] client session: onLinkFailure: 1A7399AB-2639-4E30-AE4B-9B6B5C31291B
2016-03-21 08:40:26.1,80 ThaliTest[1860:3158792] client session: disconnect
2016-03-21 08:40:26.181 ThaliTest[1860:3158792] client session: stateChange:1->0 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:5
2016-03-21 08:40:26.182 ThaliTest[1860:3158792] client session: fireConnectCallb,ack: 1A7399AB-2639-4E30-AE4B-9B6B5C31291B
,2016-03-21 08:40:26.184 ThaliTest[1860:3158792] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative Connect returned an error: Peer disconnected
INFO testThaliMobileNative Scheduling a connect retry - retries left: 1
,2016-03-21 08:40:29.192 ThaliTest[1860:3157757] jxcore: connect 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:4
2016-03-21 08:40:29.193 ThaliTest[1860:3157757] client session: connect
2016-03-21 08:40:29.193 ThaliTest[1860:3157757] client session: stateChange:0->1 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:5
,2016-03-21 08:40:29.406 ThaliTest[1860:3158792] client session: not connected 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:5
2016-03-21 08:40:29.406 ThaliTest[1860:3158792] client session: onLinkFailure: 1A7399AB-2639-4E30-AE4B-9B6B5C31291B
2016-03-21 08:40:29.4,07 ThaliTest[1860:3158792] client session: disconnect
2016-03-21 08:40:29.407 ThaliTest[1860:3158792] client session: stateChange:1->0 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:5
2016-03-21 08:40:29.408 ThaliTest[1860:3158792] client session: fireConnectCallb,ack: 1A7399AB-2639-4E30-AE4B-9B6B5C31291B
2016-03-21 08:40:29.408 ThaliTest[1860:3158792] jxcore: connect: fail: Peer disconnected
INFO testThaliMobileNative Connect returned an error: Peer disconnected
WARN testThaliMobileNative Too many connect retrie,s!
,2016-03-21 08:40:44.550 ThaliTest[1860:3157563] multipeer manager: restart client
,2016-03-21 08:40:44.567 ThaliTest[1860:3157563] client: found existing peer: 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:5
,2016-03-21 08:41:04.550 ThaliTest[1860:3157563] multipeer manager: restart client
,2016-03-21 08:41:04.566 ThaliTest[1860:3157563] client: found existing peer: 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:5
,2016-03-21 08:41:24.550 ThaliTest[1860:3157563] multipeer manager: restart client
,2016-03-21 08:41:24.568 ThaliTest[1860:3157563] client: found existing peer: 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:5
,2016-03-21 08:41:44.550 ThaliTest[1860:3157563] multipeer manager: restart client
,2016-03-21 08:41:44.569 ThaliTest[1860:3157563] client: found existing peer: 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:5
,2016-03-21 08:42:04.550 ThaliTest[1860:3157563] multipeer manager: restart client
,2016-03-21 08:42:04.567 ThaliTest[1860:3157563] client: found existing peer: 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:5
,2016-03-21 08:42:24.550 ThaliTest[1860:3157563] multipeer manager: restart client
,2016-03-21 08:42:24.567 ThaliTest[1860:3157563] client: found existing peer: 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:5
,2016-03-21 08:42:44.550 ThaliTest[1860:3157563] multipeer manager: restart client
,2016-03-21 08:42:44.567 ThaliTest[1860:3157563] client: found existing peer: 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:5
,2016-03-21 08:43:04.550 ThaliTest[1860:3157563] multipeer manager: restart client
,2016-03-21 08:43:04.567 ThaliTest[1860:3157563] client: found existing peer: 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:5
,2016-03-21 08:43:24.549 ThaliTest[1860:3157563] multipeer manager: restart client
,2016-03-21 08:43:24.568 ThaliTest[1860:3157563] client: found existing peer: 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:5
,2016-03-21 08:43:44.550 ThaliTest[1860:3157563] multipeer manager: restart client
,2016-03-21 08:43:44.567 ThaliTest[1860:3157563] client: found existing peer: 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:5
,2016-03-21 08:44:04.550 ThaliTest[1860:3157563] multipeer manager: restart client
,2016-03-21 08:44:04.570 ThaliTest[1860:3157563] client: found existing peer: 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:5
,2016-03-21 08:44:24.550 ThaliTest[1860:3157563] multipeer manager: restart client
,2016-03-21 08:44:44.549 ThaliTest[1860:3157563] multipeer manager: restart client
,2016-03-21 08:44:44.566 ThaliTest[1860:3157563] client: found existing peer: 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:5
,2016-03-21 08:45:04.550 ThaliTest[1860:3157563] multipeer manager: restart client
,2016-03-21 08:45:04.568 ThaliTest[1860:3157563] client: found existing peer: 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:5
,2016-03-21 08:45:24.550 ThaliTest[1860:3157563] multipeer manager: restart client
,2016-03-21 08:45:24.569 ThaliTest[1860:3157563] client: found existing peer: 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:5
,2016-03-21 08:45:44.550 ThaliTest[1860:3157563] multipeer manager: restart client
,2016-03-21 08:45:44.567 ThaliTest[1860:3157563] client: found existing peer: 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:5
,2016-03-21 08:46:04.550 ThaliTest[1860:3157563] multipeer manager: restart client
,2016-03-21 08:46:04.567 ThaliTest[1860:3157563] client: found existing peer: 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:5
,2016-03-21 08:46:24.550 ThaliTest[1860:3157563] multipeer manager: restart client
,2016-03-21 08:46:24.566 ThaliTest[1860:3157563] client: found existing peer: 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:5
,2016-03-21 08:46:44.550 ThaliTest[1860:3157563] multipeer manager: restart client
,2016-03-21 08:46:44.569 ThaliTest[1860:3157563] client: found existing peer: 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:5
,2016-03-21 08:47:04.550 ThaliTest[1860:3157563] multipeer manager: restart client
,2016-03-21 08:47:04.568 ThaliTest[1860:3157563] client: found existing peer: 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:5
,2016-03-21 08:47:24.550 ThaliTest[1860:3157563] multipeer manager: restart client
,2016-03-21 08:47:24.569 ThaliTest[1860:3157563] client: found existing peer: 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:5
,2016-03-21 08:47:44.550 ThaliTest[1860:3157563] multipeer manager: restart client
,2016-03-21 08:47:44.567 ThaliTest[1860:3157563] client: found existing peer: 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:5
,2016-03-21 08:48:04.550 ThaliTest[1860:3157563] multipeer manager: restart client
,2016-03-21 08:48:04.568 ThaliTest[1860:3157563] client: found existing peer: 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:5
,2016-03-21 08:48:24.550 ThaliTest[1860:3157563] multipeer manager: restart client
,2016-03-21 08:48:24.567 ThaliTest[1860:3157563] client: found existing peer: 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:5
,2016-03-21 08:48:44.550 ThaliTest[1860:3157563] multipeer manager: restart client
,2016-03-21 08:48:44.569 ThaliTest[1860:3157563] client: found existing peer: 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:5
,2016-03-21 08:49:04.550 ThaliTest[1860:3157563] multipeer manager: restart client
,2016-03-21 08:49:04.567 ThaliTest[1860:3157563] client: found existing peer: 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:5
,2016-03-21 08:49:24.550 ThaliTest[1860:3157563] multipeer manager: restart client
,2016-03-21 08:49:24.567 ThaliTest[1860:3157563] client: found existing peer: 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:5
,2016-03-21 08:49:44.550 ThaliTest[1860:3157563] multipeer manager: restart client
,2016-03-21 08:49:44.568 ThaliTest[1860:3157563] client: found existing peer: 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:5
,2016-03-21 08:50:04.550 ThaliTest[1860:3157563] multipeer manager: restart client
,2016-03-21 08:50:04.569 ThaliTest[1860:3157563] client: found existing peer: 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:5
,2016-03-21 08:50:24.550 ThaliTest[1860:3157563] multipeer manager: restart client
,2016-03-21 08:50:24.570 ThaliTest[1860:3157563] client: found existing peer: 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:5
,2016-03-21 08:50:44.550 ThaliTest[1860:3157563] multipeer manager: restart client
,2016-03-21 08:50:44.567 ThaliTest[1860:3157563] client: found existing peer: 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:5
,2016-03-21 08:51:04.550 ThaliTest[1860:3157563] multipeer manager: restart client
,2016-03-21 08:51:04.566 ThaliTest[1860:3157563] client: found existing peer: 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:5
,2016-03-21 08:51:24.549 ThaliTest[1860:3157563] multipeer manager: restart client
,2016-03-21 08:51:24.566 ThaliTest[1860:3157563] client: found existing peer: 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:5
,2016-03-21 08:51:44.550 ThaliTest[1860:3157563] multipeer manager: restart client
,2016-03-21 08:51:44.569 ThaliTest[1860:3157563] client: found existing peer: 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:5
,2016-03-21 08:52:04.550 ThaliTest[1860:3157563] multipeer manager: restart client
,2016-03-21 08:52:04.567 ThaliTest[1860:3157563] client: found existing peer: 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:5
,2016-03-21 08:52:24.550 ThaliTest[1860:3157563] multipeer manager: restart client
,2016-03-21 08:52:24.566 ThaliTest[1860:3157563] client: found existing peer: 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:5
,2016-03-21 08:52:44.550 ThaliTest[1860:3157563] multipeer manager: restart client
,2016-03-21 08:52:44.568 ThaliTest[1860:3157563] client: found existing peer: 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:5
,2016-03-21 08:53:04.550 ThaliTest[1860:3157563] multipeer manager: restart client
,2016-03-21 08:53:04.567 ThaliTest[1860:3157563] client: found existing peer: 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:5
,2016-03-21 08:53:24.550 ThaliTest[1860:3157563] multipeer manager: restart client
,2016-03-21 08:53:24.566 ThaliTest[1860:3157563] client: found existing peer: 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:5
,2016-03-21 08:53:44.550 ThaliTest[1860:3157563] multipeer manager: restart client
,2016-03-21 08:53:44.569 ThaliTest[1860:3157563] client: found existing peer: 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:5
,2016-03-21 08:54:04.550 ThaliTest[1860:3157563] multipeer manager: restart client
,2016-03-21 08:54:04.569 ThaliTest[1860:3157563] client: found existing peer: 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:5
,2016-03-21 08:54:24.550 ThaliTest[1860:3157563] multipeer manager: restart client
,2016-03-21 08:54:24.568 ThaliTest[1860:3157563] client: found existing peer: 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:5
,2016-03-21 08:54:44.550 ThaliTest[1860:3157563] multipeer manager: restart client
,2016-03-21 08:54:44.566 ThaliTest[1860:3157563] client: found existing peer: 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:5
,2016-03-21 08:55:04.550 ThaliTest[1860:3157563] multipeer manager: restart client
,2016-03-21 08:55:04.569 ThaliTest[1860:3157563] client: found existing peer: 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:5
,2016-03-21 08:55:24.550 ThaliTest[1860:3157563] multipeer manager: restart client
,2016-03-21 08:55:24.567 ThaliTest[1860:3157563] client: found existing peer: 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:5
,2016-03-21 08:55:44.550 ThaliTest[1860:3157563] multipeer manager: restart client
,2016-03-21 08:55:44.567 ThaliTest[1860:3157563] client: found existing peer: 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:5
,2016-03-21 08:56:04.550 ThaliTest[1860:3157563] multipeer manager: restart client
,2016-03-21 08:56:04.566 ThaliTest[1860:3157563] client: found existing peer: 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:5
,2016-03-21 08:56:24.550 ThaliTest[1860:3157563] multipeer manager: restart client
,2016-03-21 08:56:24.568 ThaliTest[1860:3157563] client: found existing peer: 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:5
,2016-03-21 08:56:44.550 ThaliTest[1860:3157563] multipeer manager: restart client
,2016-03-21 08:56:44.567 ThaliTest[1860:3157563] client: found existing peer: 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:5
,2016-03-21 08:57:04.550 ThaliTest[1860:3157563] multipeer manager: restart client
,2016-03-21 08:57:04.568 ThaliTest[1860:3157563] client: found existing peer: 1A7399AB-2639-4E30-AE4B-9B6B5C31291B:5

```
