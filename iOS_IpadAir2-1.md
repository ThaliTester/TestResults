#### Test 62509094c3ee53f_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/62509094c3ee53f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/8762FAD5-3CAA-468D-A5FD-902840265C41/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/8762FAD5-3CAA-468D-A5FD-902840265C41/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/62509094c3ee53f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/62509094c3ee53f/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/FB17D72A-8929-413B-9F49-D22210E92AB7/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50335"
,(lldb)     command script import "/tmp/8762FAD5-3CAA-468D-A5FD-902840265C41/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-16 10:38:02.186 ThaliTest[1577:2491351] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/32A201F3-526F-4DD8-BCD8-61AFE9512CB4/Library/Cookies/Cookies.binarycookies
,2016-03-16 10:38:02.534 ThaliTest[1577:2491351] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-16 10:38:02.535 ThaliTest[1577:2491351] Multi-tasking -> Device: YES, App: YES
,2016-03-16 10:38:02.554 ThaliTest[1577:2491351] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-16 10:38:04.528 ThaliTest[1577:2491351] Using UIWebView
,2016-03-16 10:38:04.535 ThaliTest[1577:2491351] [CDVTimer][handleopenurl] 0.379980ms
,2016-03-16 10:38:04.542 ThaliTest[1577:2491351] [CDVTimer][intentandnavigationfilter] 6.761014ms
,2016-03-16 10:38:04.543 ThaliTest[1577:2491351] [CDVTimer][gesturehandler] 0.317991ms
,2016-03-16 10:38:04.543 ThaliTest[1577:2491351] [CDVTimer][TotalPluginStartup] 9.108007ms
,2016-03-16 10:38:11.511 ThaliTest[1577:2491351] Resetting plugins due to page load.
,2016-03-16 10:38:14.770 ThaliTest[1577:2491351] Finished load of: file:///var/mobile/Containers/Bundle/Application/FB17D72A-8929-413B-9F49-D22210E92AB7/ThaliTest.app/www/index.html
,2016-03-16 10:38:14.967 ThaliTest[1577:2491351] JXcore Cordova plugin initializing
,2016-03-16 10:38:14.968 ThaliTest[1577:2491601] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-03-16 10:38:18.848 ThaliTest[1577:2491601] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-16 10:38:18.849 ThaliTest[1577:2491601] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-16 10:38:18.849 ThaliTest[1577:2491601] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-16 10:38:18.852 ThaliTest[1577:2491601] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded
,My device name is: Apple-IpadAir2-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FB17D72A-8929-413B-9F49-D22210E92AB7/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FB17D72A-8929-413B-9F49-D22210E92AB7/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FB17D72A-8929-413B-9F49-D22210E92AB7/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FB17D72A-8929-413B-9F49-D22210E92AB7/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FB17D72A-8929-413B-9F49-D22210E92AB7/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FB17D72A-8929-413B-9F49-D22210E92AB7/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FB17D72A-8929-413B-9F49-D22210E92AB7/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FB17D72A-8929-413B-9F49-D22210E92AB7/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FB17D72A-8929-413B-9F49-D22210E92AB7/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FB17D72A-8929-413B-9F49-D22210E92AB7/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FB17D72A-8929-413B-9F49-D22210E92AB7/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FB17D72A-8929-413B-9F49-D22210E92AB7/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FB17D72A-8929-413B-9F49-D22210E92AB7/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FB17D72A-8929-413B-9F49-D22210E92AB7/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FB17D72A-8929-413B-9F49-D22210E92AB7/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FB17D72A-8929-413B-9F49-D22210E92AB7/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FB17D72A-8929-413B-9F49-D22210E92AB7/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/FB17D72A-8929-413B-9F49-D22210E92AB7/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,2016-03-16 10:38:26.823 ThaliTest[1577:2491351] THREAD WARNING: ['JXcore'] took '5710.674072' ms. Plugin should use a background thread.
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
,ok 4 routerPortConnectionFailed is emitted
,# setup
,# 4. native server connections all up
,# teardown
,ok 5 Send/recvd #1 should be equal length
,ok 6 Send/recvd #1 should be same
,ok 7 Send/recvd #2 should be equal length
,ok 8 Send/recvd #2 should be same
,ok 9 Should be exactly 2 client sockets
,# setup
,# 5. native server - closing incoming stream cleans outgoing socket
,# teardown
,ok 10 socket shouldn't close until after stream
,ok 11 incoming remains open
,# setup
,# 6. native server - closing incoming connection cleans outgoing socket
,# teardown
,ok 12 we should not have gotten an error
,ok 13 socket shouldn't close until after incoming
,ok 14 incoming is cleaned up
,# setup
,# 7. native server - closing outgoing socket cleans associated mux stream
,# teardown
,ok 15 stream was closed
,ok 16 incoming should survive
,ok 17 mux should have no streams
,# setup
,# 8. native server - closing the whole server cleans everything up
,# teardown
,ok 18 we should not have gotten an error
,ok 19 Buffers are identical
,ok 20 native server is nulled out
,ok 21 native server should be closed
,ok 22 incoming has been removed
,ok 23 Incoming should be done
,ok 24 The mux object should be closed
,ok 25 The mux stream should be closed
,# setup
,# 9. native server - we can get a ton of connections and data through and still clean up the server completely
,# teardown
,ok 26 native server is nulled out
ok 27 native server should be closed
,ok 28 incoming has been removed
,# setup
,# 10. native server - simulate mux failure, make sure everything is cleaned up
,# teardown
,ok 29 we should not have gotten an error
,ok 30 Buffers are identical
,ok 31 server should be fine
,ok 32 server should be open
,ok 33 incoming has been removed
,ok 34 The mux object should be closed
,ok 35 The mux stream should be closed
,# setup
,# 11. native server - timing out the incoming connection cleans everything up
,# teardown
,ok 36 we should not have gotten an error
,ok 37 Buffers are identical
,ok 38 server should be fine
,ok 39 server should be open
,ok 40 incoming has been removed
,ok 41 The mux object should be closed
,ok 42 The mux stream should be closed
,# setup
,# 12. closeAll can close even when connections open
,# teardown
,ok 43 not possible to connect to the server anymore
,# setup
,# 13. closeAll with promise
,# teardown
,ok 44 not possible to connect to the server anymore
,# setup
,# 14. multiplex can send data
,# teardown
,ok 45 String should be length:200
,# setup
,# 15. enqueue and run in order
,# teardown
,ok 46 firstPromise setTimeout
,ok 47 firstPromise result
,ok 48 firstPromise testValue
,ok 49 secondPromise setTimeout
,ok 50 secondPromise result
,ok 51 secondPromise testValue
,ok 52 thirdPromise in promise
,ok 53 thirdPromise result
,ok 54 thirdPromise testValue
,# setup
,# 16. enqueueAtTop and run backwards
,# teardown
,ok 55 thirdPromise - first to run
,ok 56 thirdPromise - in resolve
,ok 57 secondPromise - second to run
,ok 58 secondPromise - in catch
,ok 59 firstPromise - third to run
,ok 60 firstPromise - in then
,ok 61 testing promises
,# setup
,# 17. mix enqueue and enqueueAtTop
,# teardown
,ok 62 fourth
,ok 63 fourth
,ok 64 second
,ok 65 secondPromise - in then
,ok 66 first
,ok 67 firstPromise - in catch
,ok 68 third
,ok 69 thirdPromise - in then
,ok 70 testingPromises
,# setup
,# 18. queues handled independently
,# teardown
,ok 71 all short operations completed before the long resolves
,# setup
,# 19. basic
,# teardown
,ok 72 sane
,# setup
,# 20. another
,# teardown
,ok 73 sane
,# setup
,# 21. #startListeningForAdvertisements should fail if start not called
,# teardown
,ok 74 specific error should be returned
,# setup
,ok 75 error should be null
,ok 76 error should be null
,# 22. #startUpdateAdvertisingAndListening should fail if start not called
,# teardown
,ok 77 specific error should be returned
,# setup
,ok 78 error should be null
,ok 79 error should be null
,# 23. should be able to call #stopListeningForAdvertisements many times
,# teardown
,ok 80 error should be null
,ok 81 error should be null
,ok 82 error should be null
,ok 83 error should be null
,# setup
,ok 84 error should be null
,ok 85 error should be null
,# 24. should be able to call #startListeningForAdvertisements many times
,# teardown
,ok 86 error should be null
,ok 87 error should be null
,ok 88 error should be null
,ok 89 error should be null
,# setup
,INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 90 error should be null
,ok 91 error should be null
,# 25. should be able to call #startUpdateAdvertisingAndListening many times
,# teardown
,ok 92 error should be null
,ok 93 error should be null
,ok 94 error should be null
,ok 95 error should be null
,# setup
,INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 96 error should be null
,ok 97 error should be null
,# 26. should be able to call #stopAdvertisingAndListening many times
,# teardown
,ok 98 error should be null
,ok 99 error should be null
,ok 100 error should be null
,ok 101 error should be null
,# setup
,ok 102 error should be null
,ok 103 error should be null
,# 27. #start should fail if called twice in a row
,# teardown
,ok 104 first call should succeed
,ok 105 first call should succeed
,ok 106 specific error should be returned
,# setup
,ok 107 error should be null
,ok 108 error should be null
,# 28. does not emit duplicate discoveryAdvertisingStateUpdate
,# teardown
,ok 109 called only once
,ok 110 discovery state matches
,ok 111 advertising state matches
,# setup
,INFO thaliMobile Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
,INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 112 error should be null
,ok 113 error should be null
,# 29. does not send duplicate availability changes
,# teardown
,ok 114 should be called once
,ok 115 should not have been called more than once
,# setup
,ok 116 error should be null
,ok 117 error should be null
,# 30. can get the network status
,# teardown
,ok 118 network status should have certain non-empty properties
,# setup
,ok 119 error should be null
,ok 120 error should be null
,# 31. wifi peer is marked unavailable if announcements stop
,# teardown
,ok 121 host address should match
,ok 122 port should match
,ok 123 host address should be null
,ok 124 port should should be null
,# setup
,INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 125 error should be null
,ok 126 error should be null
,# 32. Can call start/stopListeningForAdvertisements
,# teardown
,2016-03-16 10:41:54.610 ThaliTest[1577:2491601] jxcore: startListeningForAdvertisements
,2016-03-16 10:41:54.611 ThaliTest[1577:2491601] multipeer manager: start client restart timer: 0x17d91220
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-16 10:41:54.618 ThaliTest[1577:2491601] jxcore: startListeningForAdvertisements: success
,ok 127 Can call startListeningForAdvertisements without error
,2016-03-16 10:41:54.623 ThaliTest[1577:2491601] jxcore: stopListeningForAdvertisements
,2016-03-16 10:41:54.624 ThaliTest[1577:2491601] multipeer manager: stop client timer
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-16 10:41:54.629 ThaliTest[1577:2491601] jxcore: stopListeningForAdvertisements: success
,ok 128 Can call stopListeningForAdvertisements without error
,# setup
,2016-03-16 10:41:54.896 ThaliTest[1577:2491601] jxcore: stopListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-16 10:41:54.898 ThaliTest[1577:2491601] jxcore: stopListeningForAdvertisements: success
,ok 129 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-16 10:41:54.901 ThaliTest[1577:2491601] jxcore: stopAdvertisingAndListening
,2016-03-16 10:41:54.902 ThaliTest[1577:2491601] THEMultipeerManager stopping peer
,2016-03-16 10:41:54.903 ThaliTest[1577:2491601] jxcore: stopAdvertisingAndListening: success
,ok 130 Should be able to call stopAdvertisingAndListening in teardown
,# 33. Calling startListeningForAdvertisements twice is NOT an error
,# teardown
,2016-03-16 10:41:55.385 ThaliTest[1577:2491601] jxcore: startListeningForAdvertisements
,2016-03-16 10:41:55.386 ThaliTest[1577:2491601] multipeer manager: start client restart timer: 0x17d91220
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
2016-03-16 10:41:55.389 ThaliTest[1577:2491601] jxcore: startListeningForAdvertisements: success
,ok 131 Can call startListeningForAdvertisements without error
,2016-03-16 10:41:55.393 ThaliTest[1577:2491601] jxcore: startListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":true}
,2016-03-16 10:41:55.396 ThaliTest[1577:2491601] jxcore: startListeningForAdvertisements: success
,ok 132 Can call startListeningForAdvertisements twice without error
,# setup
,2016-03-16 10:41:55.551 ThaliTest[1577:2491601] jxcore: stopListeningForAdvertisements
2016-03-16 10:41:55.551 ThaliTest[1577:2491601] multipeer manager: stop client timer
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-16 10:41:55.555 ThaliTest[1577:2491601] jxcore: stopListeningForAdvertisements: success
,ok 133 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-16 10:41:55.558 ThaliTest[1577:2491601] jxcore: stopAdvertisingAndListening
,2016-03-16 10:41:55.559 ThaliTest[1577:2491601] THEMultipeerManager stopping peer
,2016-03-16 10:41:55.559 ThaliTest[1577:2491601] jxcore: stopAdvertisingAndListening: success
,ok 134 Should be able to call stopAdvertisingAndListening in teardown
,# 34. Can call start/stopUpdateAdvertisingAndListening
,# teardown
,2016-03-16 10:41:56.466 ThaliTest[1577:2491601] jxcore: startUpdateAdvertisingAndListening
,2016-03-16 10:41:56.467 ThaliTest[1577:2491601] server: starting 09320FF1-6BAC-4904-981D-AD0A579CBCDD:1
,2016-03-16 10:41:56.469 ThaliTest[1577:2491601] multipeer manager: start client restart timer: 0x17d91220
2016-03-16 10:41:56.469 ThaliTest[1577:2491601] THEMultipeerManager initialized peer 09320FF1-6BAC-4904-981D-AD0A579CBCDD:1
2016-03-16 10:41:56.470 ThaliTest[1577:2491601] jxcore: startUpdateAdvertisingAndListening: success
,ok 135 Can call startUpdateAdvertisingAndListening without error
,2016-03-16 10:41:56.474 ThaliTest[1577:2491601] jxcore: stopAdvertisingAndListening
2016-03-16 10:41:56.475 ThaliTest[1577:2491601] THEMultipeerManager stopping peer
2016-03-16 10:41:56.475 ThaliTest[1577:2491601] multipeer manager: stop client timer
,2016-03-16 10:41:56.476 ThaliTest[1577:2491601] jxcore: stopAdvertisingAndListening: success
,ok 136 Can call stopAdvertisingAndListening without error
,# setup
,2016-03-16 10:41:56.996 ThaliTest[1577:2491601] jxcore: stopListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":false,"discoveryActive":false}
,2016-03-16 10:41:56.999 ThaliTest[1577:2491601] jxcore: stopListeningForAdvertisements: success
,ok 137 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-16 10:41:57.001 ThaliTest[1577:2491601] jxcore: stopAdvertisingAndListening
,2016-03-16 10:41:57.002 ThaliTest[1577:2491601] THEMultipeerManager stopping peer
,2016-03-16 10:41:57.002 ThaliTest[1577:2491601] jxcore: stopAdvertisingAndListening: success
,ok 138 Should be able to call stopAdvertisingAndListening in teardown
,# 35. Calling startUpdateAdvertisingAndListening twice is NOT an error
,# teardown
,2016-03-16 10:41:57.594 ThaliTest[1577:2491601] jxcore: startUpdateAdvertisingAndListening
,2016-03-16 10:41:57.595 ThaliTest[1577:2491601] server: starting 09320FF1-6BAC-4904-981D-AD0A579CBCDD:2
,2016-03-16 10:41:57.596 ThaliTest[1577:2491601] multipeer manager: start client restart timer: 0x17d91220
2016-03-16 10:41:57.596 ThaliTest[1577:2491601] THEMultipeerManager initialized peer 09320FF1-6BAC-4904-981D-AD0A579CBCDD:2
2016-03-16 10:41:57.596 ThaliTest[1577:2491601] jxcore: startUpdateAdvertisingAndListening: success
,ok 139 Can call startUpdateAdvertisingAndListening without error
,2016-03-16 10:41:57.600 ThaliTest[1577:2491601] jxcore: startUpdateAdvertisingAndListening
2016-03-16 10:41:57.603 ThaliTest[1577:2491601] THEMultipeerManager stopping peer
2016-03-16 10:41:57.603 ThaliTest[1577:2491601] multipeer manager: stop client ti,mer
2016-03-16 10:41:57.604 ThaliTest[1577:2491601] server: starting 09320FF1-6BAC-4904-981D-AD0A579CBCDD:3
2016-03-16 10:41:57.605 ThaliTest[1577:2491601] multipeer manager: start client restart timer: 0x17d91220
2016-03-16 10:41:57.605 ThaliTest[1577:2491601] THEMultipeerManager initialized peer 09320FF1-6BAC-4904-981D-AD0A579CBCDD:3
,2016-03-16 10:41:57.608 ThaliTest[1577:2491601] jxcore: startUpdateAdvertisingAndListening: success
,ok 140 Can call startUpdateAdvertisingAndListening twice without error
,# setup
,2016-03-16 10:41:57.984 ThaliTest[1577:2491601] jxcore: stopListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-16 10:41:57.986 ThaliTest[1577:2491601] jxcore: stopListeningForAdvertisements: success
,ok 141 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-16 10:41:57.989 ThaliTest[1577:2491601] jxcore: stopAdvertisingAndListening
,2016-03-16 10:41:57.989 ThaliTest[1577:2491601] THEMultipeerManager stopping peer
,2016-03-16 10:41:57.990 ThaliTest[1577:2491601] multipeer manager: stop client timer
2016-03-16 10:41:57.991 ThaliTest[1577:2491601] jxcore: stopAdvertisingAndListening: success
,ok 142 Should be able to call stopAdvertisingAndListening in teardown
,# 36. peerAvailabilityChange is called
,# teardown
,2016-03-16 10:41:58.245 ThaliTest[1577:2491601] jxcore: startUpdateAdvertisingAndListening
2016-03-16 10:41:58.246 ThaliTest[1577:2491601] server: starting 09320FF1-6BAC-4904-981D-AD0A579CBCDD:4
,2016-03-16 10:41:58.247 ThaliTest[1577:2491601] multipeer manager: start client restart timer: 0x17d91220
2016-03-16 10:41:58.247 ThaliTest[1577:2491601] THEMultipeerManager initialized peer 09320FF1-6BAC-4904-981D-AD0A579CBCDD:4
2016-03-16 10:41:58.247 ThaliTest[1577:2491601] jxcore: startUpdateAdvertisingAndListening: success
,ok 143 Can call startUpdateAdvertisingAndListeningwithout error
,2016-03-16 10:41:58.250 ThaliTest[1577:2491601] jxcore: startListeningForAdvertisements
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-16 10:41:58.253 ThaliTest[1577:2491601] jxcore: startListeningForAdvertisements: success
,ok 144 Can call startListeningForAdvertisements without error
,2016-03-16 10:41:59.539 ThaliTest[1577:2491351] client: found new peer: 5E5A0952-8249-4E01-B982-15843F7A65D1:4
,ok 145 peers must be an array
,ok 146 peers must not be zero-length
,ok 147 peer must have peerIdentifier
,ok 148 peerIdentifier must be a string
,ok 149 peer must have peerAvailable
,ok 150 peer must have pleaseConnect
,# setup
,2016-03-16 10:42:00.343 ThaliTest[1577:2491601] jxcore: stopListeningForAdvertisements
,INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":false}
,2016-03-16 10:42:00.346 ThaliTest[1577:2491601] jxcore: stopListeningForAdvertisements: success
,ok 151 Should be able to call stopListeningForAdvertisments in teardown
,2016-03-16 10:42:00.349 ThaliTest[1577:2491601] jxcore: stopAdvertisingAndListening
,2016-03-16 10:42:00.349 ThaliTest[1577:2491601] THEMultipeerManager stopping peer
,2016-03-16 10:42:00.350 ThaliTest[1577:2491601] multipeer manager: stop client timer
,2016-03-16 10:42:00.353 ThaliTest[1577:2491601] jxcore: stopAdvertisingAndListening: success
ok 152 Should be able to call stopAdvertisingAndListening in teardown
,# 37. Can connect to a remote peer
,# teardown
,2016-03-16 10:42:01.211 ThaliTest[1577:2491601] jxcore: startUpdateAdvertisingAndListening
,2016-03-16 10:42:01.212 ThaliTest[1577:2491601] server: starting 09320FF1-6BAC-4904-981D-AD0A579CBCDD:5
,2016-03-16 10:42:01.213 ThaliTest[1577:2491601] multipeer manager: start client restart timer: 0x17d91220
2016-03-16 10:42:01.214 ThaliTest[1577:2491601] THEMultipeerManager initialized peer 09320FF1-6BAC-4904-981D-AD0A579CBCDD:5
2016-03-16 10:42:01.214 ThaliTest[1577:2491601] jxcore: startUpdateAdvertisingAndListening: success
,ok 153 Can call startUpdateAdvertisingAndListening without error
,2016-03-16 10:42:01.217 ThaliTest[1577:2491601] jxcore: startListeningForAdvertisements
INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"advertisingActive":true,"discoveryActive":true}
2016-03-16 10:42:01.219 ThaliTest[1577:2491601] jxcore: startListeningForAdvertisements: success
ok 154 Can call startListeningForAdvertisements without error
,2016-03-16 10:42:01.494 ThaliTest[1577:2491351] client: found new peer: 5E5A0952-8249-4E01-B982-15843F7A65D1:4
,2016-03-16 10:42:01.496 ThaliTest[1577:2491601] jxcore: connect 5E5A0952-8249-4E01-B982-15843F7A65D1:4
2016-03-16 10:42:01.497 ThaliTest[1577:2491601] client: server will connect
,2016-03-16 10:42:01.498 ThaliTest[1577:2491601] client session: reverseConnect
,2016-03-16 10:42:01.499 ThaliTest[1577:2491601] client session: stateChange:0->1 5E5A0952-8249-4E01-B982-15843F7A65D1:4
,2016-03-16 10:42:02.275 ThaliTest[1577:2491351] multipeer session: reset timer
,2016-03-16 10:42:02.275 ThaliTest[1577:2491351] server: rejecting invitation from 5E5A0952-8249-4E01-B982-15843F7A65D1 due to previous generation (09320FF1-6BAC-4904-981D-AD0A579CBCDD:5 != 09320FF1-6BAC-4904-981D-AD0A579CBCDD:4)
,2016-03-16 10:42:02.306 ThaliTest[1577:2492005] client session: not connected 5E5A0952-8249-4E01-B982-15843F7A65D1:4
2016-03-16 10:42:02.306 ThaliTest[1577:2492005] client session: onLinkFailure: 5E5A0952-8249-4E01-B982-15843F7A65D1
2016-03-16 10:42:02.307 ThaliTest[1577:2492005] client session: disconnect
,2016-03-16 10:42:02.307 ThaliTest[1577:2492005] client session: stateChange:1->0 5E5A0952-8249-4E01-B982-15843F7A65D1:4
,2016-03-16 10:42:02.307 ThaliTest[1577:2492005] client session: no connect callback (server initiated)
,2016-03-16 10:42:21.215 ThaliTest[1577:2491351] multipeer manager: restart client
,2016-03-16 10:42:21.229 ThaliTest[1577:2491351] client: found updated peer: 5E5A0952-8249-4E01-B982-15843F7A65D1:5
,2016-03-16 10:42:41.215 ThaliTest[1577:2491351] multipeer manager: restart client
,2016-03-16 10:42:41.228 ThaliTest[1577:2491351] client: found existing peer: 5E5A0952-8249-4E01-B982-15843F7A65D1:5
,2016-03-16 10:43:01.215 ThaliTest[1577:2491351] multipeer manager: restart client
,2016-03-16 10:43:01.229 ThaliTest[1577:2491351] client: found existing peer: 5E5A0952-8249-4E01-B982-15843F7A65D1:5
,2016-03-16 10:43:21.215 ThaliTest[1577:2491351] multipeer manager: restart client
,2016-03-16 10:43:21.230 ThaliTest[1577:2491351] client: found existing peer: 5E5A0952-8249-4E01-B982-15843F7A65D1:5
,2016-03-16 10:43:41.215 ThaliTest[1577:2491351] multipeer manager: restart client
,2016-03-16 10:43:41.229 ThaliTest[1577:2491351] client: found existing peer: 5E5A0952-8249-4E01-B982-15843F7A65D1:5
,2016-03-16 10:44:01.215 ThaliTest[1577:2491351] multipeer manager: restart client
,2016-03-16 10:44:01.228 ThaliTest[1577:2491351] client: found existing peer: 5E5A0952-8249-4E01-B982-15843F7A65D1:5
,2016-03-16 10:44:21.215 ThaliTest[1577:2491351] multipeer manager: restart client
,2016-03-16 10:44:21.229 ThaliTest[1577:2491351] client: found existing peer: 5E5A0952-8249-4E01-B982-15843F7A65D1:5
,2016-03-16 10:44:41.215 ThaliTest[1577:2491351] multipeer manager: restart client
,2016-03-16 10:44:41.230 ThaliTest[1577:2491351] client: found existing peer: 5E5A0952-8249-4E01-B982-15843F7A65D1:5
,2016-03-16 10:45:01.215 ThaliTest[1577:2491351] multipeer manager: restart client
,2016-03-16 10:45:01.230 ThaliTest[1577:2491351] client: found existing peer: 5E5A0952-8249-4E01-B982-15843F7A65D1:5
,2016-03-16 10:45:21.215 ThaliTest[1577:2491351] multipeer manager: restart client
,2016-03-16 10:45:21.228 ThaliTest[1577:2491351] client: found existing peer: 5E5A0952-8249-4E01-B982-15843F7A65D1:5
,2016-03-16 10:45:41.215 ThaliTest[1577:2491351] multipeer manager: restart client
,2016-03-16 10:45:41.228 ThaliTest[1577:2491351] client: found existing peer: 5E5A0952-8249-4E01-B982-15843F7A65D1:5
,2016-03-16 10:46:01.215 ThaliTest[1577:2491351] multipeer manager: restart client
,2016-03-16 10:46:01.234 ThaliTest[1577:2491351] client: found existing peer: 5E5A0952-8249-4E01-B982-15843F7A65D1:5
,2016-03-16 10:46:21.215 ThaliTest[1577:2491351] multipeer manager: restart client
,2016-03-16 10:46:21.229 ThaliTest[1577:2491351] client: found existing peer: 5E5A0952-8249-4E01-B982-15843F7A65D1:5
,2016-03-16 10:46:41.215 ThaliTest[1577:2491351] multipeer manager: restart client
,2016-03-16 10:46:41.227 ThaliTest[1577:2491351] client: found existing peer: 5E5A0952-8249-4E01-B982-15843F7A65D1:5
,2016-03-16 10:47:01.215 ThaliTest[1577:2491351] multipeer manager: restart client
,2016-03-16 10:47:01.228 ThaliTest[1577:2491351] client: found existing peer: 5E5A0952-8249-4E01-B982-15843F7A65D1:5
,2016-03-16 10:47:21.215 ThaliTest[1577:2491351] multipeer manager: restart client
,2016-03-16 10:47:21.230 ThaliTest[1577:2491351] client: found existing peer: 5E5A0952-8249-4E01-B982-15843F7A65D1:5
,2016-03-16 10:47:41.215 ThaliTest[1577:2491351] multipeer manager: restart client
,2016-03-16 10:47:41.228 ThaliTest[1577:2491351] client: found existing peer: 5E5A0952-8249-4E01-B982-15843F7A65D1:5
,2016-03-16 10:48:01.215 ThaliTest[1577:2491351] multipeer manager: restart client
,2016-03-16 10:48:01.230 ThaliTest[1577:2491351] client: found existing peer: 5E5A0952-8249-4E01-B982-15843F7A65D1:5
,2016-03-16 10:48:21.215 ThaliTest[1577:2491351] multipeer manager: restart client
,2016-03-16 10:48:21.230 ThaliTest[1577:2491351] client: found existing peer: 5E5A0952-8249-4E01-B982-15843F7A65D1:5
,2016-03-16 10:48:41.214 ThaliTest[1577:2491351] multipeer manager: restart client
,2016-03-16 10:48:41.229 ThaliTest[1577:2491351] client: found existing peer: 5E5A0952-8249-4E01-B982-15843F7A65D1:5
,2016-03-16 10:49:01.215 ThaliTest[1577:2491351] multipeer manager: restart client
,2016-03-16 10:49:01.230 ThaliTest[1577:2491351] client: found existing peer: 5E5A0952-8249-4E01-B982-15843F7A65D1:5
,2016-03-16 10:49:21.215 ThaliTest[1577:2491351] multipeer manager: restart client
,2016-03-16 10:49:21.227 ThaliTest[1577:2491351] client: found existing peer: 5E5A0952-8249-4E01-B982-15843F7A65D1:5
,2016-03-16 10:49:41.215 ThaliTest[1577:2491351] multipeer manager: restart client
,2016-03-16 10:49:41.231 ThaliTest[1577:2491351] client: found existing peer: 5E5A0952-8249-4E01-B982-15843F7A65D1:5
,2016-03-16 10:50:01.215 ThaliTest[1577:2491351] multipeer manager: restart client
,2016-03-16 10:50:01.230 ThaliTest[1577:2491351] client: found existing peer: 5E5A0952-8249-4E01-B982-15843F7A65D1:5
,2016-03-16 10:50:21.215 ThaliTest[1577:2491351] multipeer manager: restart client
,2016-03-16 10:50:21.229 ThaliTest[1577:2491351] client: found existing peer: 5E5A0952-8249-4E01-B982-15843F7A65D1:5
,2016-03-16 10:50:41.215 ThaliTest[1577:2491351] multipeer manager: restart client
,2016-03-16 10:50:41.228 ThaliTest[1577:2491351] client: found existing peer: 5E5A0952-8249-4E01-B982-15843F7A65D1:5
,2016-03-16 10:51:01.215 ThaliTest[1577:2491351] multipeer manager: restart client
,2016-03-16 10:51:01.229 ThaliTest[1577:2491351] client: found existing peer: 5E5A0952-8249-4E01-B982-15843F7A65D1:5
,2016-03-16 10:51:21.215 ThaliTest[1577:2491351] multipeer manager: restart client
,2016-03-16 10:51:21.229 ThaliTest[1577:2491351] client: found existing peer: 5E5A0952-8249-4E01-B982-15843F7A65D1:5
,2016-03-16 10:51:41.215 ThaliTest[1577:2491351] multipeer manager: restart client
,2016-03-16 10:51:41.230 ThaliTest[1577:2491351] client: found existing peer: 5E5A0952-8249-4E01-B982-15843F7A65D1:5
,2016-03-16 10:52:01.215 ThaliTest[1577:2491351] multipeer manager: restart client
,2016-03-16 10:52:01.229 ThaliTest[1577:2491351] client: found existing peer: 5E5A0952-8249-4E01-B982-15843F7A65D1:5
,2016-03-16 10:52:21.215 ThaliTest[1577:2491351] multipeer manager: restart client
,2016-03-16 10:52:21.229 ThaliTest[1577:2491351] client: found existing peer: 5E5A0952-8249-4E01-B982-15843F7A65D1:5
,2016-03-16 10:52:41.215 ThaliTest[1577:2491351] multipeer manager: restart client
,2016-03-16 10:52:41.227 ThaliTest[1577:2491351] client: found existing peer: 5E5A0952-8249-4E01-B982-15843F7A65D1:5
,2016-03-16 10:53:01.215 ThaliTest[1577:2491351] multipeer manager: restart client
,2016-03-16 10:53:01.228 ThaliTest[1577:2491351] client: found existing peer: 5E5A0952-8249-4E01-B982-15843F7A65D1:5
,2016-03-16 10:53:21.215 ThaliTest[1577:2491351] multipeer manager: restart client
,2016-03-16 10:53:21.229 ThaliTest[1577:2491351] client: found existing peer: 5E5A0952-8249-4E01-B982-15843F7A65D1:5
,2016-03-16 10:53:41.215 ThaliTest[1577:2491351] multipeer manager: restart client
,2016-03-16 10:53:41.231 ThaliTest[1577:2491351] client: found existing peer: 5E5A0952-8249-4E01-B982-15843F7A65D1:5
,2016-03-16 10:54:01.215 ThaliTest[1577:2491351] multipeer manager: restart client
,2016-03-16 10:54:01.229 ThaliTest[1577:2491351] client: found existing peer: 5E5A0952-8249-4E01-B982-15843F7A65D1:5
,2016-03-16 10:54:21.215 ThaliTest[1577:2491351] multipeer manager: restart client
,2016-03-16 10:54:21.229 ThaliTest[1577:2491351] client: found existing peer: 5E5A0952-8249-4E01-B982-15843F7A65D1:5
,2016-03-16 10:54:41.215 ThaliTest[1577:2491351] multipeer manager: restart client
,2016-03-16 10:54:41.229 ThaliTest[1577:2491351] client: found existing peer: 5E5A0952-8249-4E01-B982-15843F7A65D1:5
,2016-03-16 10:55:01.215 ThaliTest[1577:2491351] multipeer manager: restart client
,2016-03-16 10:55:01.229 ThaliTest[1577:2491351] client: found existing peer: 5E5A0952-8249-4E01-B982-15843F7A65D1:5
,2016-03-16 10:55:21.215 ThaliTest[1577:2491351] multipeer manager: restart client
,2016-03-16 10:55:21.229 ThaliTest[1577:2491351] client: found existing peer: 5E5A0952-8249-4E01-B982-15843F7A65D1:5
,2016-03-16 10:55:41.215 ThaliTest[1577:2491351] multipeer manager: restart client
,2016-03-16 10:55:41.230 ThaliTest[1577:2491351] client: found existing peer: 5E5A0952-8249-4E01-B982-15843F7A65D1:5
,2016-03-16 10:56:01.215 ThaliTest[1577:2491351] multipeer manager: restart client
,2016-03-16 10:56:01.230 ThaliTest[1577:2491351] client: found existing peer: 5E5A0952-8249-4E01-B982-15843F7A65D1:5
,2016-03-16 10:56:21.215 ThaliTest[1577:2491351] multipeer manager: restart client
,2016-03-16 10:56:21.228 ThaliTest[1577:2491351] client: found existing peer: 5E5A0952-8249-4E01-B982-15843F7A65D1:5
,2016-03-16 10:56:41.215 ThaliTest[1577:2491351] multipeer manager: restart client
,2016-03-16 10:56:41.229 ThaliTest[1577:2491351] client: found existing peer: 5E5A0952-8249-4E01-B982-15843F7A65D1:5
,2016-03-16 10:57:01.215 ThaliTest[1577:2491351] multipeer manager: restart client
,2016-03-16 10:57:01.228 ThaliTest[1577:2491351] client: found existing peer: 5E5A0952-8249-4E01-B982-15843F7A65D1:5
,2016-03-16 10:57:21.215 ThaliTest[1577:2491351] multipeer manager: restart client
,2016-03-16 10:57:21.229 ThaliTest[1577:2491351] client: found existing peer: 5E5A0952-8249-4E01-B982-15843F7A65D1:5
,2016-03-16 10:57:41.215 ThaliTest[1577:2491351] multipeer manager: restart client
,2016-03-16 10:57:41.229 ThaliTest[1577:2491351] client: found existing peer: 5E5A0952-8249-4E01-B982-15843F7A65D1:5
,2016-03-16 10:58:01.215 ThaliTest[1577:2491351] multipeer manager: restart client
,2016-03-16 10:58:01.229 ThaliTest[1577:2491351] client: found existing peer: 5E5A0952-8249-4E01-B982-15843F7A65D1:5
,2016-03-16 10:58:21.215 ThaliTest[1577:2491351] multipeer manager: restart client
,2016-03-16 10:58:21.228 ThaliTest[1577:2491351] client: found existing peer: 5E5A0952-8249-4E01-B982-15843F7A65D1:5
,2016-03-16 10:58:41.215 ThaliTest[1577:2491351] multipeer manager: restart client
,2016-03-16 10:58:41.229 ThaliTest[1577:2491351] client: found existing peer: 5E5A0952-8249-4E01-B982-15843F7A65D1:5
,2016-03-16 10:59:01.215 ThaliTest[1577:2491351] multipeer manager: restart client
,2016-03-16 10:59:01.228 ThaliTest[1577:2491351] client: found existing peer: 5E5A0952-8249-4E01-B982-15843F7A65D1:5
,2016-03-16 10:59:21.215 ThaliTest[1577:2491351] multipeer manager: restart client
,2016-03-16 10:59:21.229 ThaliTest[1577:2491351] client: found existing peer: 5E5A0952-8249-4E01-B982-15843F7A65D1:5
,2016-03-16 10:59:41.215 ThaliTest[1577:2491351] multipeer manager: restart client
,2016-03-16 10:59:41.228 ThaliTest[1577:2491351] client: found existing peer: 5E5A0952-8249-4E01-B982-15843F7A65D1:5

```
