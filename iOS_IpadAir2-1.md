#### Test 625481247d7767b_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/625481247d7767b/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/D362092C-9980-4199-87E5-291C6DB43242/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/D362092C-9980-4199-87E5-291C6DB43242/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/625481247d7767b/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/625481247d7767b/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/C103EF73-0D4F-44ED-9E3E-3FD7B7131D83/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49703"
,(lldb)     command script import "/tmp/D362092C-9980-4199-87E5-291C6DB43242/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-15 15:00:47.385 ThaliTest[1498:2364214] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/614A17DC-2F19-450D-86EE-DC2C5AF3BAF4/Library/Cookies/Cookies.binarycookies
,2016-03-15 15:00:47.717 ThaliTest[1498:2364214] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-15 15:00:47.718 ThaliTest[1498:2364214] Multi-tasking -> Device: YES, App: YES
,2016-03-15 15:00:47.734 ThaliTest[1498:2364214] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-15 15:00:49.451 ThaliTest[1498:2364214] Using UIWebView
,2016-03-15 15:00:49.459 ThaliTest[1498:2364214] [CDVTimer][handleopenurl] 0.557005ms
,2016-03-15 15:00:49.466 ThaliTest[1498:2364214] [CDVTimer][intentandnavigationfilter] 6.517053ms
,2016-03-15 15:00:49.466 ThaliTest[1498:2364214] [CDVTimer][gesturehandler] 0.322998ms
,2016-03-15 15:00:49.467 ThaliTest[1498:2364214] [CDVTimer][TotalPluginStartup] 8.975983ms
,2016-03-15 15:00:56.254 ThaliTest[1498:2364214] Resetting plugins due to page load.
,2016-03-15 15:00:59.577 ThaliTest[1498:2364214] Finished load of: file:///var/mobile/Containers/Bundle/Application/C103EF73-0D4F-44ED-9E3E-3FD7B7131D83/ThaliTest.app/www/index.html
,2016-03-15 15:00:59.769 ThaliTest[1498:2364214] JXcore Cordova plugin initializing
,2016-03-15 15:00:59.770 ThaliTest[1498:2364461] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,INFO testUtils: Toggling radios to: true

,Unit Test app is loaded

,My device name is: Apple-IpadAir2-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C103EF73-0D4F-44ED-9E3E-3FD7B7131D83/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C103EF73-0D4F-44ED-9E3E-3FD7B7131D83/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C103EF73-0D4F-44ED-9E3E-3FD7B7131D83/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C103EF73-0D4F-44ED-9E3E-3FD7B7131D83/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C103EF73-0D4F-44ED-9E3E-3FD7B7131D83/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C103EF73-0D4F-44ED-9E3E-3FD7B7131D83/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js

,2016-03-15 15:01:12.930 ThaliTest[1498:2364461] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-15 15:01:12.930 ThaliTest[1498:2364461] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-15 15:01:12.930 ThaliTest[1498:2364461] jxcore: didRegisterToNative networkChanged
,2016-03-15 15:01:12.931 ThaliTest[1498:2364461] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C103EF73-0D4F-44ED-9E3E-3FD7B7131D83/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C103EF73-0D4F-44ED-9E3E-3FD7B7131D83/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C103EF73-0D4F-44ED-9E3E-3FD7B7131D83/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C103EF73-0D4F-44ED-9E3E-3FD7B7131D83/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C103EF73-0D4F-44ED-9E3E-3FD7B7131D83/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C103EF73-0D4F-44ED-9E3E-3FD7B7131D83/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C103EF73-0D4F-44ED-9E3E-3FD7B7131D83/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C103EF73-0D4F-44ED-9E3E-3FD7B7131D83/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C103EF73-0D4F-44ED-9E3E-3FD7B7131D83/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C103EF73-0D4F-44ED-9E3E-3FD7B7131D83/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C103EF73-0D4F-44ED-9E3E-3FD7B7131D83/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C103EF73-0D4F-44ED-9E3E-3FD7B7131D83/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js

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

,ok 27 native server should be closed

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

ok 47 firstPromise result

ok 48 firstPromise testValue

,ok 49 secondPromise setTimeout

ok 50 secondPromise result

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

ok 70 testingPromises

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

,2016-03-15 15:04:26.481 ThaliTest[1498:2364461] jxcore: stopListeningForAdvertisements
,2016-03-15 15:04:26.483 ThaliTest[1498:2364461] jxcore: stopListeningForAdvertisements: success
,ok 80 error should be null

,ok 81 error should be null

,2016-03-15 15:04:26.488 ThaliTest[1498:2364461] jxcore: stopListeningForAdvertisements
,2016-03-15 15:04:26.489 ThaliTest[1498:2364461] jxcore: stopListeningForAdvertisements: success
,ok 82 error should be null

,ok 83 error should be null

,# setup

,2016-03-15 15:04:26.747 ThaliTest[1498:2364461] jxcore: stopAdvertisingAndListening
,2016-03-15 15:04:26.748 ThaliTest[1498:2364461] THEMultipeerManager stopping peer
,2016-03-15 15:04:26.748 ThaliTest[1498:2364461] jxcore: stopAdvertisingAndListening: success
,2016-03-15 15:04:26.750 ThaliTest[1498:2364461] jxcore: stopListeningForAdvertisements
,2016-03-15 15:04:26.752 ThaliTest[1498:2364461] jxcore: stopListeningForAdvertisements: success
,ok 84 error should be null

,ok 85 error should be null

,# 24. should be able to call #startListeningForAdvertisements many times

,# teardown

,2016-03-15 15:04:27.049 ThaliTest[1498:2364461] jxcore: startListeningForAdvertisements
,2016-03-15 15:04:27.051 ThaliTest[1498:2364461] multipeer manager: start client restart timer: 0x8b73b0
,2016-03-15 15:04:27.053 ThaliTest[1498:2364461] jxcore: startListeningForAdvertisements: success
,ok 86 error should be null

,ok 87 error should be null

,2016-03-15 15:04:27.079 ThaliTest[1498:2364461] jxcore: startListeningForAdvertisements
,2016-03-15 15:04:27.080 ThaliTest[1498:2364461] jxcore: startListeningForAdvertisements: success
,ok 88 error should be null

,ok 89 error should be null

,# setup

,2016-03-15 15:04:27.313 ThaliTest[1498:2364461] jxcore: stopAdvertisingAndListening
2016-03-15 15:04:27.313 ThaliTest[1498:2364461] THEMultipeerManager stopping peer
,2016-03-15 15:04:27.314 ThaliTest[1498:2364461] jxcore: stopAdvertisingAndListening: success
,2016-03-15 15:04:27.315 ThaliTest[1498:2364461] jxcore: stopListeningForAdvertisements
,2016-03-15 15:04:27.316 ThaliTest[1498:2364461] multipeer manager: stop client timer
,2016-03-15 15:04:27.319 ThaliTest[1498:2364461] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).

,ok 90 error should be null

,ok 91 error should be null

,# 25. should be able to call #startUpdateAdvertisingAndListening many times

,# teardown

,2016-03-15 15:04:27.919 ThaliTest[1498:2364461] jxcore: startUpdateAdvertisingAndListening
,2016-03-15 15:04:27.919 ThaliTest[1498:2364461] server: starting 1EDC4A2C-FB25-4DBE-BC67-F66F43BAAA73:1
,2016-03-15 15:04:27.921 ThaliTest[1498:2364461] multipeer manager: start client restart timer: 0x8b73b0
2016-03-15 15:04:27.921 ThaliTest[1498:2364461] THEMultipeerManager initialized peer 1EDC4A2C-FB25-4DBE-BC67-F66F43BAAA73:1
2016-03-15 15:04:27.922 ThaliTest[1498:2364461] jxcore: startUpdateAdvertisingAndListening: success
,ok 92 error should be null

,ok 93 error should be null

,2016-03-15 15:04:27.953 ThaliTest[1498:2364461] jxcore: startUpdateAdvertisingAndListening
,2016-03-15 15:04:27.954 ThaliTest[1498:2364461] THEMultipeerManager stopping peer
2016-03-15 15:04:27.955 ThaliTest[1498:2364461] multipeer manager: stop client timer
,2016-03-15 15:04:27.955 ThaliTest[1498:2364461] server: starting 1EDC4A2C-FB25-4DBE-BC67-F66F43BAAA73:2
,2016-03-15 15:04:27.959 ThaliTest[1498:2364461] multipeer manager: start client restart timer: 0x8b73b0
2016-03-15 15:04:27.959 ThaliTest[1498:2364461] THEMultipeerManager initialized peer 1EDC4A2C-FB25-4DBE-BC67-F66F43BAAA73:2
2016-03-15 15:04:27.960 Th,aliTest[1498:2364461] jxcore: startUpdateAdvertisingAndListening: success
,ok 94 error should be null

,ok 95 error should be null

,# setup

,2016-03-15 15:04:28.978 ThaliTest[1498:2364461] jxcore: stopAdvertisingAndListening
2016-03-15 15:04:28.979 ThaliTest[1498:2364461] THEMultipeerManager stopping peer
,2016-03-15 15:04:28.980 ThaliTest[1498:2364461] multipeer manager: stop client timer
,2016-03-15 15:04:28.980 ThaliTest[1498:2364461] jxcore: stopAdvertisingAndListening: success
2016-03-15 15:04:28.982 ThaliTest[1498:2364461] jxcore: stopListeningForAdvertisements
,2016-03-15 15:04:28.986 ThaliTest[1498:2364461] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).

,ok 96 error should be null

,ok 97 error should be null

,# 26. should be able to call #stopAdvertisingAndListening many times

,# teardown

,2016-03-15 15:04:29.543 ThaliTest[1498:2364461] jxcore: stopAdvertisingAndListening
,2016-03-15 15:04:29.544 ThaliTest[1498:2364461] THEMultipeerManager stopping peer
,2016-03-15 15:04:29.544 ThaliTest[1498:2364461] jxcore: stopAdvertisingAndListening: success
,ok 98 error should be null

,ok 99 error should be null

,2016-03-15 15:04:29.550 ThaliTest[1498:2364461] jxcore: stopAdvertisingAndListening
,2016-03-15 15:04:29.551 ThaliTest[1498:2364461] THEMultipeerManager stopping peer
,2016-03-15 15:04:29.551 ThaliTest[1498:2364461] jxcore: stopAdvertisingAndListening: success
,ok 100 error should be null

,ok 101 error should be null

,# setup

,2016-03-15 15:04:29.917 ThaliTest[1498:2364461] jxcore: stopAdvertisingAndListening
,2016-03-15 15:04:29.918 ThaliTest[1498:2364461] THEMultipeerManager stopping peer
,2016-03-15 15:04:29.918 ThaliTest[1498:2364461] jxcore: stopAdvertisingAndListening: success
,2016-03-15 15:04:29.920 ThaliTest[1498:2364461] jxcore: stopListeningForAdvertisements
,2016-03-15 15:04:29.921 ThaliTest[1498:2364461] jxcore: stopListeningForAdvertisements: success
,ok 102 error should be null

,ok 103 error should be null

,# 27. #start should fail if called twice in a row

,# teardown

,ok 104 first call should succeed

,ok 105 first call should succeed

,ok 106 specific error should be returned

,# setup

,2016-03-15 15:04:30.658 ThaliTest[1498:2364461] jxcore: stopAdvertisingAndListening
,2016-03-15 15:04:30.659 ThaliTest[1498:2364461] THEMultipeerManager stopping peer
2016-03-15 15:04:30.660 ThaliTest[1498:2364461] jxcore: stopAdvertisingAndListening: success
,2016-03-15 15:04:30.661 ThaliTest[1498:2364461] jxcore: stopListeningForAdvertisements
,2016-03-15 15:04:30.662 ThaliTest[1498:2364461] jxcore: stopListeningForAdvertisements: success
,ok 107 error should be null

,ok 108 error should be null

,# 28. does not emit duplicate discoveryAdvertisingStateUpdate

,# teardown

,2016-03-15 15:04:31.159 ThaliTest[1498:2364461] jxcore: startListeningForAdvertisements
,2016-03-15 15:04:31.160 ThaliTest[1498:2364461] multipeer manager: start client restart timer: 0x8b73b0
,2016-03-15 15:04:31.161 ThaliTest[1498:2364461] jxcore: startListeningForAdvertisements: success
,2016-03-15 15:04:31.174 ThaliTest[1498:2364461] jxcore: startUpdateAdvertisingAndListening
,2016-03-15 15:04:31.175 ThaliTest[1498:2364461] server: starting 1EDC4A2C-FB25-4DBE-BC67-F66F43BAAA73:3
,2016-03-15 15:04:31.177 ThaliTest[1498:2364461] THEMultipeerManager initialized peer 1EDC4A2C-FB25-4DBE-BC67-F66F43BAAA73:3
2016-03-15 15:04:31.177 ThaliTest[1498:2364461] jxcore: startUpdateAdvertisingAndListening: success
,ok 109 called only once

,ok 110 discovery state matches

,ok 111 advertising state matches

,# setup

,2016-03-15 15:04:31.512 ThaliTest[1498:2364461] jxcore: stopAdvertisingAndListening
2016-03-15 15:04:31.512 ThaliTest[1498:2364461] THEMultipeerManager stopping peer
,2016-03-15 15:04:31.513 ThaliTest[1498:2364461] jxcore: stopAdvertisingAndListening: success
,2016-03-15 15:04:31.515 ThaliTest[1498:2364461] jxcore: stopListeningForAdvertisements
,2016-03-15 15:04:31.515 ThaliTest[1498:2364461] multipeer manager: stop client timer
,2016-03-15 15:04:31.519 ThaliTest[1498:2364461] jxcore: stopListeningForAdvertisements: success
,INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}

,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).

,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).

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

,ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined

,ok 121 host address should match

,ok 122 port should match

,ok 123 host address should be null

,ok 124 port should should be null

,# setup

,INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).

,ok 125 error should be null

,ok 126 error should be null

,# 32. Can call start/stopListeningForAdvertisements

,# teardown

,2016-03-15 15:04:37.808 ThaliTest[1498:2364461] jxcore: startListeningForAdvertisements
,2016-03-15 15:04:37.809 ThaliTest[1498:2364461] multipeer manager: start client restart timer: 0x8b73b0
,2016-03-15 15:04:37.810 ThaliTest[1498:2364461] jxcore: startListeningForAdvertisements: success
ok 127 Can call startListeningForAdvertisements without error

,2016-03-15 15:04:37.813 ThaliTest[1498:2364461] jxcore: stopListeningForAdvertisements
,2016-03-15 15:04:37.814 ThaliTest[1498:2364461] multipeer manager: stop client timer
,2016-03-15 15:04:37.816 ThaliTest[1498:2364461] jxcore: stopListeningForAdvertisements: success
,ok 128 Can call stopListeningForAdvertisements without error

,# setup

,2016-03-15 15:04:38.387 ThaliTest[1498:2364461] jxcore: stopAdvertisingAndListening
2016-03-15 15:04:38.388 ThaliTest[1498:2364461] THEMultipeerManager stopping peer
,2016-03-15 15:04:38.388 ThaliTest[1498:2364461] jxcore: stopAdvertisingAndListening: success
,2016-03-15 15:04:38.389 ThaliTest[1498:2364461] jxcore: stopListeningForAdvertisements
,2016-03-15 15:04:38.391 ThaliTest[1498:2364461] jxcore: stopListeningForAdvertisements: success
,# 33. Calling startListeningForAdvertisements twice is NOT an error

,# teardown

,2016-03-15 15:04:39.489 ThaliTest[1498:2364461] jxcore: startListeningForAdvertisements
,2016-03-15 15:04:39.490 ThaliTest[1498:2364461] multipeer manager: start client restart timer: 0x8b73b0
,2016-03-15 15:04:39.492 ThaliTest[1498:2364461] jxcore: startListeningForAdvertisements: success
,ok 129 Can call startListeningForAdvertisements without error

,2016-03-15 15:04:39.494 ThaliTest[1498:2364461] jxcore: startListeningForAdvertisements
,2016-03-15 15:04:39.497 ThaliTest[1498:2364461] jxcore: startListeningForAdvertisements: success
,ok 130 Can call startListeningForAdvertisements twice without error

,# setup

,2016-03-15 15:04:39.926 ThaliTest[1498:2364461] jxcore: stopAdvertisingAndListening
2016-03-15 15:04:39.927 ThaliTest[1498:2364461] THEMultipeerManager stopping peer
,2016-03-15 15:04:39.928 ThaliTest[1498:2364461] jxcore: stopAdvertisingAndListening: success
,2016-03-15 15:04:39.929 ThaliTest[1498:2364461] jxcore: stopListeningForAdvertisements
2016-03-15 15:04:39.929 ThaliTest[1498:2364461] multipeer manager: stop client timer
,2016-03-15 15:04:39.932 ThaliTest[1498:2364461] jxcore: stopListeningForAdvertisements: success
,# 34. Can call start/stopUpdateAdvertisingAndListening

,# teardown

,2016-03-15 15:04:40.492 ThaliTest[1498:2364461] jxcore: startUpdateAdvertisingAndListening
2016-03-15 15:04:40.493 ThaliTest[1498:2364461] server: starting 1EDC4A2C-FB25-4DBE-BC67-F66F43BAAA73:4
,2016-03-15 15:04:40.494 ThaliTest[1498:2364461] multipeer manager: start client restart timer: 0x8b73b0
2016-03-15 15:04:40.495 ThaliTest[1498:2364461] THEMultipeerManager initialized peer 1EDC4A2C-FB25-4DBE-BC67-F66F43BAAA73:4
2016-03-15 15:04:40.495 Th,aliTest[1498:2364461] jxcore: startUpdateAdvertisingAndListening: success
ok 131 Can call startUpdateAdvertisingAndListening without error

2016-03-15 15:04:40.497 ThaliTest[1498:2364461] jxcore: stopAdvertisingAndListening
,2016-03-15 15:04:40.497 ThaliTest[1498:2364461] THEMultipeerManager stopping peer
,2016-03-15 15:04:40.498 ThaliTest[1498:2364461] multipeer manager: stop client timer
,2016-03-15 15:04:40.499 ThaliTest[1498:2364461] jxcore: stopAdvertisingAndListening: success
ok 132 Can call stopAdvertisingAndListening without error

,# setup

,2016-03-15 15:04:40.966 ThaliTest[1498:2364461] jxcore: stopAdvertisingAndListening
,2016-03-15 15:04:40.967 ThaliTest[1498:2364461] THEMultipeerManager stopping peer
,2016-03-15 15:04:40.967 ThaliTest[1498:2364461] jxcore: stopAdvertisingAndListening: success
,2016-03-15 15:04:40.969 ThaliTest[1498:2364461] jxcore: stopListeningForAdvertisements
,2016-03-15 15:04:40.970 ThaliTest[1498:2364461] jxcore: stopListeningForAdvertisements: success
,# 35. Calling startUpdateAdvertisingAndListening twice is NOT an error

,# teardown

,2016-03-15 15:04:41.592 ThaliTest[1498:2364461] jxcore: startUpdateAdvertisingAndListening
2016-03-15 15:04:41.592 ThaliTest[1498:2364461] server: starting 1EDC4A2C-FB25-4DBE-BC67-F66F43BAAA73:5
,2016-03-15 15:04:41.594 ThaliTest[1498:2364461] multipeer manager: start client restart timer: 0x8b73b0
2016-03-15 15:04:41.594 ThaliTest[1498:2364461] THEMultipeerManager initialized peer 1EDC4A2C-FB25-4DBE-BC67-F66F43BAAA73:5
2016-03-15 15:04:41.594 ThaliTest[1498:2364461] jxcore: startUpdateAdvertisingAndListening: success
ok 133 Can call startUpdateAdvertisingAndListening without error

,2016-03-15 15:04:41.598 ThaliTest[1498:2364461] jxcore: startUpdateAdvertisingAndListening
2016-03-15 15:04:41.598 ThaliTest[1498:2364461] THEMultipeerManager stopping peer
2016-03-15 15:04:41.601 ThaliTest[1498:2364461] multipeer manager: stop client timer
2016-03-15 15:04:41.601 ThaliTest[1498:2364461] server: starting 1EDC4A2C-FB25-4DBE-BC67-F66F43BAAA73:6
,2016-03-15 15:04:41.602 ThaliTest[1498:2364461] multipeer manager: start client restart timer: 0x8b73b0
2016-03-15 15:04:41.603 ThaliTest[1498:2364461] THEMultipeerManager initialized peer 1EDC4A2C-FB25-4DBE-BC67-F66F43BAAA73:6
2016-03-15 15:04:41.603 Th,aliTest[1498:2364461] jxcore: startUpdateAdvertisingAndListening: success
ok 134 Can call startUpdateAdvertisingAndListening twice without error

,# setup

,2016-03-15 15:04:41.880 ThaliTest[1498:2364461] jxcore: stopAdvertisingAndListening
,2016-03-15 15:04:41.881 ThaliTest[1498:2364461] THEMultipeerManager stopping peer
,2016-03-15 15:04:41.881 ThaliTest[1498:2364461] multipeer manager: stop client timer
2016-03-15 15:04:41.883 ThaliTest[1498:2364461] jxcore: stopAdvertisingAndListening: success
,2016-03-15 15:04:41.885 ThaliTest[1498:2364461] jxcore: stopListeningForAdvertisements
2016-03-15 15:04:41.887 ThaliTest[1498:2364461] jxcore: stopListeningForAdvertisements: success
,# 36. peerAvailabilityChange is called

,# teardown

,2016-03-15 15:04:43.992 ThaliTest[1498:2364461] jxcore: startUpdateAdvertisingAndListening
,2016-03-15 15:04:43.992 ThaliTest[1498:2364461] server: starting 1EDC4A2C-FB25-4DBE-BC67-F66F43BAAA73:7
,2016-03-15 15:04:43.993 ThaliTest[1498:2364461] multipeer manager: start client restart timer: 0x8b73b0
2016-03-15 15:04:43.994 ThaliTest[1498:2364461] THEMultipeerManager initialized peer 1EDC4A2C-FB25-4DBE-BC67-F66F43BAAA73:7
2016-03-15 15:04:43.994 ThaliTest[1498:2364461] jxcore: startUpdateAdvertisingAndListening: success
,ok 135 Can call startUpdateAdvertisingAndListeningwithout error

2016-03-15 15:04:43.997 ThaliTest[1498:2364461] jxcore: startListeningForAdvertisements
,2016-03-15 15:04:44.000 ThaliTest[1498:2364461] jxcore: startListeningForAdvertisements: success
,ok 136 Can call startListeningForAdvertisements without error

,2016-03-15 15:04:44.848 ThaliTest[1498:2364214] client: found new peer: 0A147418-2D09-407B-8ED7-4D439DFED9FC:7
,ok 137 peer must have peerIdentifier

,ok 138 peerIdentifier must be a string

,# setup

,2016-03-15 15:04:45.699 ThaliTest[1498:2364461] jxcore: stopAdvertisingAndListening
,2016-03-15 15:04:45.700 ThaliTest[1498:2364461] THEMultipeerManager stopping peer
,2016-03-15 15:04:45.701 ThaliTest[1498:2364461] jxcore: stopAdvertisingAndListening: success
,2016-03-15 15:04:45.702 ThaliTest[1498:2364461] jxcore: stopListeningForAdvertisements
2016-03-15 15:04:45.703 ThaliTest[1498:2364461] multipeer manager: stop client timer
,2016-03-15 15:04:45.705 ThaliTest[1498:2364461] jxcore: stopListeningForAdvertisements: success
,# 37. Can connect to a remote peer

,# teardown

,2016-03-15 15:04:46.241 ThaliTest[1498:2364461] jxcore: startUpdateAdvertisingAndListening
,2016-03-15 15:04:46.242 ThaliTest[1498:2364461] server: starting 1EDC4A2C-FB25-4DBE-BC67-F66F43BAAA73:8
,2016-03-15 15:04:46.243 ThaliTest[1498:2364461] multipeer manager: start client restart timer: 0x8b73b0
2016-03-15 15:04:46.243 ThaliTest[1498:2364461] THEMultipeerManager initialized peer 1EDC4A2C-FB25-4DBE-BC67-F66F43BAAA73:8
2016-03-15 15:04:46.243 ThaliTest[1498:2364461] jxcore: startUpdateAdvertisingAndListening: success
,ok 139 Can call startUpdateAdvertisingAndListening without error

2016-03-15 15:04:46.247 ThaliTest[1498:2364461] jxcore: startListeningForAdvertisements
2016-03-15 15:04:46.248 ThaliTest[1498:2364461] jxcore: startListeningForAdvertisements: success
ok 140 Can call startListeningForAdvertisements without error

,2016-03-15 15:04:46.911 ThaliTest[1498:2364214] client: found new peer: 0A147418-2D09-407B-8ED7-4D439DFED9FC:7
,2016-03-15 15:04:46.927 ThaliTest[1498:2364461] jxcore: connect 0A147418-2D09-407B-8ED7-4D439DFED9FC:7
2016-03-15 15:04:46.928 ThaliTest[1498:2364461] client session: connect
,2016-03-15 15:04:46.929 ThaliTest[1498:2364461] client session: stateChange:0->1 0A147418-2D09-407B-8ED7-4D439DFED9FC:7
,2016-03-15 15:04:47.329 ThaliTest[1498:2364857] client session: not connected 0A147418-2D09-407B-8ED7-4D439DFED9FC:7
2016-03-15 15:04:47.329 ThaliTest[1498:2364857] client session: onLinkFailure: 0A147418-2D09-407B-8ED7-4D439DFED9FC
2016-03-15 15:04:47.3,30 ThaliTest[1498:2364857] client session: disconnect
2016-03-15 15:04:47.330 ThaliTest[1498:2364857] client session: stateChange:1->0 0A147418-2D09-407B-8ED7-4D439DFED9FC:7
,2016-03-15 15:04:47.331 ThaliTest[1498:2364857] client session: fireConnectCallback: 0A147418-2D09-407B-8ED7-4D439DFED9FC
,2016-03-15 15:04:47.332 ThaliTest[1498:2364857] jxcore: connect: fail: Peer disconnected
,not ok 141 Error from connect: Peer disconnected

  ---

,    operator: fail

  ...

,# setup

,2016-03-15 15:04:48.272 ThaliTest[1498:2364214] multipeer session: reset timer
2016-03-15 15:04:48.273 ThaliTest[1498:2364214] server: rejecting invitation from 0A147418-2D09-407B-8ED7-4D439DFED9FC due to previous generation (1EDC4A2C-FB25-4DBE-BC67-F66F4,3BAAA73:8 != 1EDC4A2C-FB25-4DBE-BC67-F66F43BAAA73:7)
,2016-03-15 15:05:06.244 ThaliTest[1498:2364214] multipeer manager: restart client
,2016-03-15 15:05:06.257 ThaliTest[1498:2364214] client: found updated peer: 0A147418-2D09-407B-8ED7-4D439DFED9FC:8
,2016-03-15 15:05:26.244 ThaliTest[1498:2364214] multipeer manager: restart client
,2016-03-15 15:05:26.259 ThaliTest[1498:2364214] client: found existing peer: 0A147418-2D09-407B-8ED7-4D439DFED9FC:8
,2016-03-15 15:05:46.244 ThaliTest[1498:2364214] multipeer manager: restart client
,2016-03-15 15:05:46.259 ThaliTest[1498:2364214] client: found existing peer: 0A147418-2D09-407B-8ED7-4D439DFED9FC:8
,2016-03-15 15:06:06.244 ThaliTest[1498:2364214] multipeer manager: restart client
,2016-03-15 15:06:06.259 ThaliTest[1498:2364214] client: found existing peer: 0A147418-2D09-407B-8ED7-4D439DFED9FC:8
,2016-03-15 15:06:26.244 ThaliTest[1498:2364214] multipeer manager: restart client
,2016-03-15 15:06:26.258 ThaliTest[1498:2364214] client: found existing peer: 0A147418-2D09-407B-8ED7-4D439DFED9FC:8
,2016-03-15 15:06:46.244 ThaliTest[1498:2364214] multipeer manager: restart client
,2016-03-15 15:06:46.259 ThaliTest[1498:2364214] client: found existing peer: 0A147418-2D09-407B-8ED7-4D439DFED9FC:8
,2016-03-15 15:07:06.244 ThaliTest[1498:2364214] multipeer manager: restart client
,2016-03-15 15:07:06.258 ThaliTest[1498:2364214] client: found existing peer: 0A147418-2D09-407B-8ED7-4D439DFED9FC:8
,2016-03-15 15:07:26.244 ThaliTest[1498:2364214] multipeer manager: restart client
,2016-03-15 15:07:26.258 ThaliTest[1498:2364214] client: found existing peer: 0A147418-2D09-407B-8ED7-4D439DFED9FC:8
,2016-03-15 15:07:46.244 ThaliTest[1498:2364214] multipeer manager: restart client
,2016-03-15 15:07:46.258 ThaliTest[1498:2364214] client: found existing peer: 0A147418-2D09-407B-8ED7-4D439DFED9FC:8
,2016-03-15 15:08:06.244 ThaliTest[1498:2364214] multipeer manager: restart client
,2016-03-15 15:08:06.258 ThaliTest[1498:2364214] client: found existing peer: 0A147418-2D09-407B-8ED7-4D439DFED9FC:8
,2016-03-15 15:08:26.244 ThaliTest[1498:2364214] multipeer manager: restart client
,2016-03-15 15:08:26.258 ThaliTest[1498:2364214] client: found existing peer: 0A147418-2D09-407B-8ED7-4D439DFED9FC:8
,2016-03-15 15:08:46.244 ThaliTest[1498:2364214] multipeer manager: restart client
,2016-03-15 15:08:46.258 ThaliTest[1498:2364214] client: found existing peer: 0A147418-2D09-407B-8ED7-4D439DFED9FC:8
,2016-03-15 15:09:06.244 ThaliTest[1498:2364214] multipeer manager: restart client
,2016-03-15 15:09:06.258 ThaliTest[1498:2364214] client: found existing peer: 0A147418-2D09-407B-8ED7-4D439DFED9FC:8
,2016-03-15 15:09:26.244 ThaliTest[1498:2364214] multipeer manager: restart client
,2016-03-15 15:09:26.259 ThaliTest[1498:2364214] client: found existing peer: 0A147418-2D09-407B-8ED7-4D439DFED9FC:8
,2016-03-15 15:09:46.244 ThaliTest[1498:2364214] multipeer manager: restart client
,2016-03-15 15:09:46.259 ThaliTest[1498:2364214] client: found existing peer: 0A147418-2D09-407B-8ED7-4D439DFED9FC:8
,2016-03-15 15:10:06.244 ThaliTest[1498:2364214] multipeer manager: restart client
,2016-03-15 15:10:06.260 ThaliTest[1498:2364214] client: found existing peer: 0A147418-2D09-407B-8ED7-4D439DFED9FC:8
,2016-03-15 15:10:26.243 ThaliTest[1498:2364214] multipeer manager: restart client
,2016-03-15 15:10:26.257 ThaliTest[1498:2364214] client: found existing peer: 0A147418-2D09-407B-8ED7-4D439DFED9FC:8
,2016-03-15 15:10:46.244 ThaliTest[1498:2364214] multipeer manager: restart client
,2016-03-15 15:10:46.260 ThaliTest[1498:2364214] client: found existing peer: 0A147418-2D09-407B-8ED7-4D439DFED9FC:8
,2016-03-15 15:11:06.244 ThaliTest[1498:2364214] multipeer manager: restart client
,2016-03-15 15:11:06.258 ThaliTest[1498:2364214] client: found existing peer: 0A147418-2D09-407B-8ED7-4D439DFED9FC:8
,2016-03-15 15:11:26.244 ThaliTest[1498:2364214] multipeer manager: restart client
,2016-03-15 15:11:26.258 ThaliTest[1498:2364214] client: found existing peer: 0A147418-2D09-407B-8ED7-4D439DFED9FC:8
,2016-03-15 15:11:46.244 ThaliTest[1498:2364214] multipeer manager: restart client
,2016-03-15 15:11:46.259 ThaliTest[1498:2364214] client: found existing peer: 0A147418-2D09-407B-8ED7-4D439DFED9FC:8
,2016-03-15 15:12:06.244 ThaliTest[1498:2364214] multipeer manager: restart client
,2016-03-15 15:12:06.258 ThaliTest[1498:2364214] client: found existing peer: 0A147418-2D09-407B-8ED7-4D439DFED9FC:8
,2016-03-15 15:12:26.244 ThaliTest[1498:2364214] multipeer manager: restart client
,2016-03-15 15:12:26.260 ThaliTest[1498:2364214] client: found existing peer: 0A147418-2D09-407B-8ED7-4D439DFED9FC:8
,2016-03-15 15:12:46.244 ThaliTest[1498:2364214] multipeer manager: restart client
,2016-03-15 15:12:46.258 ThaliTest[1498:2364214] client: found existing peer: 0A147418-2D09-407B-8ED7-4D439DFED9FC:8
,2016-03-15 15:13:06.244 ThaliTest[1498:2364214] multipeer manager: restart client
,2016-03-15 15:13:06.259 ThaliTest[1498:2364214] client: found existing peer: 0A147418-2D09-407B-8ED7-4D439DFED9FC:8
,2016-03-15 15:13:26.244 ThaliTest[1498:2364214] multipeer manager: restart client
,2016-03-15 15:13:26.258 ThaliTest[1498:2364214] client: found existing peer: 0A147418-2D09-407B-8ED7-4D439DFED9FC:8
,2016-03-15 15:13:46.244 ThaliTest[1498:2364214] multipeer manager: restart client
,2016-03-15 15:13:46.259 ThaliTest[1498:2364214] client: found existing peer: 0A147418-2D09-407B-8ED7-4D439DFED9FC:8
,2016-03-15 15:14:06.244 ThaliTest[1498:2364214] multipeer manager: restart client
,2016-03-15 15:14:06.258 ThaliTest[1498:2364214] client: found existing peer: 0A147418-2D09-407B-8ED7-4D439DFED9FC:8
,2016-03-15 15:14:26.244 ThaliTest[1498:2364214] multipeer manager: restart client
,2016-03-15 15:14:26.259 ThaliTest[1498:2364214] client: found existing peer: 0A147418-2D09-407B-8ED7-4D439DFED9FC:8
,2016-03-15 15:14:46.244 ThaliTest[1498:2364214] multipeer manager: restart client
,2016-03-15 15:14:46.257 ThaliTest[1498:2364214] client: found existing peer: 0A147418-2D09-407B-8ED7-4D439DFED9FC:8
,2016-03-15 15:15:06.244 ThaliTest[1498:2364214] multipeer manager: restart client
,2016-03-15 15:15:06.259 ThaliTest[1498:2364214] client: found existing peer: 0A147418-2D09-407B-8ED7-4D439DFED9FC:8
,2016-03-15 15:15:26.244 ThaliTest[1498:2364214] multipeer manager: restart client
,2016-03-15 15:15:26.258 ThaliTest[1498:2364214] client: found existing peer: 0A147418-2D09-407B-8ED7-4D439DFED9FC:8
,2016-03-15 15:15:46.244 ThaliTest[1498:2364214] multipeer manager: restart client
,2016-03-15 15:15:46.259 ThaliTest[1498:2364214] client: found existing peer: 0A147418-2D09-407B-8ED7-4D439DFED9FC:8
,2016-03-15 15:16:06.244 ThaliTest[1498:2364214] multipeer manager: restart client
,2016-03-15 15:16:06.260 ThaliTest[1498:2364214] client: found existing peer: 0A147418-2D09-407B-8ED7-4D439DFED9FC:8
,2016-03-15 15:16:26.244 ThaliTest[1498:2364214] multipeer manager: restart client
,2016-03-15 15:16:26.258 ThaliTest[1498:2364214] client: found existing peer: 0A147418-2D09-407B-8ED7-4D439DFED9FC:8
,2016-03-15 15:16:46.244 ThaliTest[1498:2364214] multipeer manager: restart client
,2016-03-15 15:16:46.260 ThaliTest[1498:2364214] client: found existing peer: 0A147418-2D09-407B-8ED7-4D439DFED9FC:8
,2016-03-15 15:17:06.244 ThaliTest[1498:2364214] multipeer manager: restart client
,2016-03-15 15:17:06.259 ThaliTest[1498:2364214] client: found existing peer: 0A147418-2D09-407B-8ED7-4D439DFED9FC:8
,2016-03-15 15:17:26.244 ThaliTest[1498:2364214] multipeer manager: restart client
,2016-03-15 15:17:26.259 ThaliTest[1498:2364214] client: found existing peer: 0A147418-2D09-407B-8ED7-4D439DFED9FC:8
,2016-03-15 15:17:46.244 ThaliTest[1498:2364214] multipeer manager: restart client
,2016-03-15 15:17:46.259 ThaliTest[1498:2364214] client: found existing peer: 0A147418-2D09-407B-8ED7-4D439DFED9FC:8
,2016-03-15 15:18:06.244 ThaliTest[1498:2364214] multipeer manager: restart client
,2016-03-15 15:18:06.259 ThaliTest[1498:2364214] client: found existing peer: 0A147418-2D09-407B-8ED7-4D439DFED9FC:8
,2016-03-15 15:18:26.244 ThaliTest[1498:2364214] multipeer manager: restart client
,2016-03-15 15:18:26.257 ThaliTest[1498:2364214] client: found existing peer: 0A147418-2D09-407B-8ED7-4D439DFED9FC:8
,2016-03-15 15:18:46.244 ThaliTest[1498:2364214] multipeer manager: restart client
,2016-03-15 15:18:46.258 ThaliTest[1498:2364214] client: found existing peer: 0A147418-2D09-407B-8ED7-4D439DFED9FC:8
,2016-03-15 15:19:06.244 ThaliTest[1498:2364214] multipeer manager: restart client
,2016-03-15 15:19:06.258 ThaliTest[1498:2364214] client: found existing peer: 0A147418-2D09-407B-8ED7-4D439DFED9FC:8
,2016-03-15 15:19:26.244 ThaliTest[1498:2364214] multipeer manager: restart client
,2016-03-15 15:19:26.259 ThaliTest[1498:2364214] client: found existing peer: 0A147418-2D09-407B-8ED7-4D439DFED9FC:8
,2016-03-15 15:19:46.244 ThaliTest[1498:2364214] multipeer manager: restart client
,2016-03-15 15:19:46.257 ThaliTest[1498:2364214] client: found existing peer: 0A147418-2D09-407B-8ED7-4D439DFED9FC:8
,2016-03-15 15:20:06.244 ThaliTest[1498:2364214] multipeer manager: restart client
,2016-03-15 15:20:06.261 ThaliTest[1498:2364214] client: found existing peer: 0A147418-2D09-407B-8ED7-4D439DFED9FC:8
,2016-03-15 15:20:26.244 ThaliTest[1498:2364214] multipeer manager: restart client
,2016-03-15 15:20:26.260 ThaliTest[1498:2364214] client: found existing peer: 0A147418-2D09-407B-8ED7-4D439DFED9FC:8
,2016-03-15 15:20:46.244 ThaliTest[1498:2364214] multipeer manager: restart client
,2016-03-15 15:20:46.259 ThaliTest[1498:2364214] client: found existing peer: 0A147418-2D09-407B-8ED7-4D439DFED9FC:8
,2016-03-15 15:21:06.244 ThaliTest[1498:2364214] multipeer manager: restart client
,2016-03-15 15:21:06.258 ThaliTest[1498:2364214] client: found existing peer: 0A147418-2D09-407B-8ED7-4D439DFED9FC:8
,2016-03-15 15:21:26.244 ThaliTest[1498:2364214] multipeer manager: restart client
,2016-03-15 15:21:26.258 ThaliTest[1498:2364214] client: found existing peer: 0A147418-2D09-407B-8ED7-4D439DFED9FC:8
,2016-03-15 15:21:46.244 ThaliTest[1498:2364214] multipeer manager: restart client
,2016-03-15 15:21:46.257 ThaliTest[1498:2364214] client: found existing peer: 0A147418-2D09-407B-8ED7-4D439DFED9FC:8

```
