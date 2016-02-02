#### Test 575312431be71d2_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/575312431be71d2/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/BF94A105-0BDD-496F-8172-4039F17D36E2/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/BF94A105-0BDD-496F-8172-4039F17D36E2/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/575312431be71d2/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/575312431be71d2/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/2AE5E8C3-8706-4764-9580-211A7FED60B2/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64385"
,(lldb)     command script import "/tmp/BF94A105-0BDD-496F-8172-4039F17D36E2/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-02 14:16:29.659 ThaliTest[453:684757] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/50A9F3FD-997F-4E0A-AEE6-61BBEEF8EB46/Library/Cookies/Cookies.binarycookies
,2016-02-02 14:16:30.022 ThaliTest[453:684757] Apache Cordova native platform version 3.9.2 is starting.
,2016-02-02 14:16:30.023 ThaliTest[453:684757] Multi-tasking -> Device: YES, App: YES
,2016-02-02 14:16:30.032 ThaliTest[453:684757] Unlimited access to network resources
,2016-02-02 14:16:30.042 ThaliTest[453:684757] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-02 14:16:40.085 ThaliTest[453:684757] Resetting plugins due to page load.
,2016-02-02 14:16:43.788 ThaliTest[453:684757] Finished load of: file:///var/mobile/Containers/Bundle/Application/2AE5E8C3-8706-4764-9580-211A7FED60B2/ThaliTest.app/www/index.html
,2016-02-02 14:16:43.943 ThaliTest[453:684757] JXcore Cordova plugin initializing
,2016-02-02 14:16:43.943 ThaliTest[453:685018] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-IpadAir2-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2AE5E8C3-8706-4764-9580-211A7FED60B2/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2AE5E8C3-8706-4764-9580-211A7FED60B2/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2AE5E8C3-8706-4764-9580-211A7FED60B2/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2AE5E8C3-8706-4764-9580-211A7FED60B2/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/2AE5E8C3-8706-4764-9580-211A7FED60B2/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded

,TAP version 13

,# setup

,# multiplex can send data

,# teardown

,ok 1 String should be length:200

,# setup

,# enqueue and run in order

,# teardown

,ok 2 firstPromise setTimeout

,ok 3 firstPromise result

,ok 4 firstPromise testValue

,ok 5 secondPromise setTimeout

,ok 6 secondPromise result

,ok 7 secondPromise testValue

,ok 8 thirdPromise in promise

,ok 9 thirdPromise result

,ok 10 thirdPromise testValue

,# setup

,# basic

,# teardown

,ok 11 sane

,# setup

,# another

,# teardown

,ok 12 sane

,# setup

,# Can call start/stopListeningForAdvertisements

,# teardown

,2016-02-02 14:21:13.521 ThaliTest[453:685018] jxcore: startListeningForAdvertisements
,2016-02-02 14:21:13.523 ThaliTest[453:685018] multipeer manager: start client restart timer: 0x15d59350
,2016-02-02 14:21:13.524 ThaliTest[453:685018] jxcore: startListeningForAdvertisements: success
,ok 13 Can call startListeningForAdvertisements without error

,2016-02-02 14:21:13.527 ThaliTest[453:685018] jxcore: stopListeningForAdvertisements
2016-02-02 14:21:13.528 ThaliTest[453:685018] multipeer manager: stop client timer
2016-02-02 14:21:13.528 ThaliTest[453:685018] jxcore: stopListeningForAdvertisements: ,success
ok 14 Can call stopListeningForAdvertisements without error

,# setup

,2016-02-02 14:21:13.765 ThaliTest[453:685018] jxcore: stopListeningForAdvertisements
,2016-02-02 14:21:13.765 ThaliTest[453:685018] jxcore: stopListeningForAdvertisements: success
,ok 15 Should be able to call stopListeningForAdvertisments in teardown

,2016-02-02 14:21:13.768 ThaliTest[453:685018] jxcore: stopAdvertisingAndListening
2016-02-02 14:21:13.768 ThaliTest[453:685018] THEMultipeerManager stopping peer
,2016-02-02 14:21:13.768 ThaliTest[453:685018] jxcore: stopAdvertisingAndListening: success
,ok 16 Should be able to call stopAdvertisingAndListening in teardown

,# Calling startListeningForAdvertisements twice is an error

,# teardown

,2016-02-02 14:21:14.358 ThaliTest[453:685018] jxcore: startListeningForAdvertisements
,2016-02-02 14:21:14.359 ThaliTest[453:685018] multipeer manager: start client restart timer: 0x15d59350
2016-02-02 14:21:14.359 ThaliTest[453:685018] jxcore: startListeningForAdvertisements: success
,ok 17 Can call startListeningForAdvertisements without error

,2016-02-02 14:21:14.362 ThaliTest[453:685018] jxcore: startListeningForAdvertisements
2016-02-02 14:21:14.362 ThaliTest[453:685018] jxcore: startListeningForAdvertisements: failure
ok 18 Calling start twice is an error

,ok 19 Error must be "Call Stop!"

,# setup

,2016-02-02 14:21:14.385 ThaliTest[453:685018] jxcore: stopListeningForAdvertisements
2016-02-02 14:21:14.386 ThaliTest[453:685018] multipeer manager: stop client timer
,2016-02-02 14:21:14.387 ThaliTest[453:685018] jxcore: stopListeningForAdvertisements: success
,ok 20 Should be able to call stopListeningForAdvertisments in teardown

,2016-02-02 14:21:14.390 ThaliTest[453:685018] jxcore: stopAdvertisingAndListening
,2016-02-02 14:21:14.391 ThaliTest[453:685018] THEMultipeerManager stopping peer
2016-02-02 14:21:14.391 ThaliTest[453:685018] jxcore: stopAdvertisingAndListening: success
,ok 21 Should be able to call stopAdvertisingAndListening in teardown

,# Can call start/stopUpdateAdvertisingAndListening

,# teardown

,2016-02-02 14:21:14.511 ThaliTest[453:685018] jxcore: startUpdateAdvertisingAndListening
,2016-02-02 14:21:14.512 ThaliTest[453:685018] server: starting B0673E8C-23B0-4E2C-B7F0-E2565174D20F:1
,2016-02-02 14:21:14.513 ThaliTest[453:685018] multipeer manager: start client restart timer: 0x15d59350
2016-02-02 14:21:14.514 ThaliTest[453:685018] THEMultipeerManager initialized peer B0673E8C-23B0-4E2C-B7F0-E2565174D20F:1
,2016-02-02 14:21:14.514 ThaliTest[453:685018] jxcore: startUpdateAdvertisingAndListening: success
,ok 22 Can call startUpdateAdvertisingAndListening without error

2016-02-02 14:21:14.518 ThaliTest[453:685018] jxcore: stopAdvertisingAndListening
2016-02-02 14:21:14.518 ThaliTest[453:685018] THEMultipeerManager stopping peer
2016-02-02 14:21:14.519 T,haliTest[453:685018] multipeer manager: stop client timer
2016-02-02 14:21:14.519 ThaliTest[453:685018] jxcore: stopAdvertisingAndListening: success
,ok 23 Can call stopAdvertisingAndListening without error

,# setup

,2016-02-02 14:21:15.412 ThaliTest[453:685018] jxcore: stopListeningForAdvertisements
2016-02-02 14:21:15.412 ThaliTest[453:685018] jxcore: stopListeningForAdvertisements: success
,ok 24 Should be able to call stopListeningForAdvertisments in teardown

,2016-02-02 14:21:15.414 ThaliTest[453:685018] jxcore: stopAdvertisingAndListening
,2016-02-02 14:21:15.414 ThaliTest[453:685018] THEMultipeerManager stopping peer
,2016-02-02 14:21:15.414 ThaliTest[453:685018] jxcore: stopAdvertisingAndListening: success
,ok 25 Should be able to call stopAdvertisingAndListening in teardown

,# Calling startUpdateAdvertisingAndListening twice is NOT and error

,# teardown

,2016-02-02 14:21:20.785 ThaliTest[453:685018] jxcore: startUpdateAdvertisingAndListening
,2016-02-02 14:21:20.786 ThaliTest[453:685018] server: starting B0673E8C-23B0-4E2C-B7F0-E2565174D20F:2
,2016-02-02 14:21:20.787 ThaliTest[453:685018] multipeer manager: start client restart timer: 0x15d59350
2016-02-02 14:21:20.787 ThaliTest[453:685018] THEMultipeerManager initialized peer B0673E8C-23B0-4E2C-B7F0-E2565174D20F:2
2016-02-02 14:21:20.787 ThaliTest[453:685018] jxcore: startUpdateAdvertisingAndListening: success
ok 26 Can call startUpdateAdvertisingAndListening without error

,2016-02-02 14:21:20.791 ThaliTest[453:685018] jxcore: startUpdateAdvertisingAndListening
2016-02-02 14:21:20.791 ThaliTest[453:685018] THEMultipeerManager stopping peer
2016-02-02 14:21:20.792 ThaliTest[453:685018] multipeer manager: stop client timer
2,016-02-02 14:21:20.792 ThaliTest[453:685018] server: starting B0673E8C-23B0-4E2C-B7F0-E2565174D20F:3
2016-02-02 14:21:20.793 ThaliTest[453:685018] multipeer manager: start client restart timer: 0x15d59350
2016-02-02 14:21:20.794 ThaliTest[453:685018] THE,MultipeerManager initialized peer B0673E8C-23B0-4E2C-B7F0-E2565174D20F:3
2016-02-02 14:21:20.794 ThaliTest[453:685018] jxcore: startUpdateAdvertisingAndListening: success
,ok 27 Can call startUpdateAdvertisingAndListening twice without error

,# setup

,2016-02-02 14:21:21.055 ThaliTest[453:685018] jxcore: stopListeningForAdvertisements
,2016-02-02 14:21:21.055 ThaliTest[453:685018] jxcore: stopListeningForAdvertisements: success
,ok 28 Should be able to call stopListeningForAdvertisments in teardown

,2016-02-02 14:21:21.058 ThaliTest[453:685018] jxcore: stopAdvertisingAndListening
,2016-02-02 14:21:21.058 ThaliTest[453:685018] THEMultipeerManager stopping peer
,2016-02-02 14:21:21.059 ThaliTest[453:685018] multipeer manager: stop client timer
2016-02-02 14:21:21.060 ThaliTest[453:685018] jxcore: stopAdvertisingAndListening: success
ok 29 Should be able to call stopAdvertisingAndListening in teardown

,# peerAvailabilityChange is called

,# teardown

,2016-02-02 14:21:21.268 ThaliTest[453:685018] jxcore: startUpdateAdvertisingAndListening
2016-02-02 14:21:21.269 ThaliTest[453:685018] server: starting B0673E8C-23B0-4E2C-B7F0-E2565174D20F:4
,2016-02-02 14:21:21.270 ThaliTest[453:685018] multipeer manager: start client restart timer: 0x15d59350
2016-02-02 14:21:21.271 ThaliTest[453:685018] THEMultipeerManager initialized peer B0673E8C-23B0-4E2C-B7F0-E2565174D20F:4
2016-02-02 14:21:21.271 Thal,iTest[453:685018] jxcore: startUpdateAdvertisingAndListening: success
ok 30 Can call startUpdateAdvertisingAndListeningwithout error

,2016-02-02 14:21:21.274 ThaliTest[453:685018] jxcore: startListeningForAdvertisements
2016-02-02 14:21:21.274 ThaliTest[453:685018] multipeer manager: stop client timer
2016-02-02 14:21:21.275 ThaliTest[453:685018] multipeer manager: start client restart timer: 0x15d59350
2016-02-02 14:21:21.275 ThaliTest[453:685018] jxcore: startListeningForAdvertisements: success
,ok 31 Can call startListeningForAdvertisements without error

,2016-02-02 14:21:28.790 ThaliTest[453:684757] client: found new peer: AC42391D-3B67-44B2-83EF-6199949E75E1:4
,ok 32 peers must be an array

,ok 33 peers must not be zero-length

,ok 34 peer must have peerIdentifier

,ok 35 peerIdentifier must be a string

,ok 36 peer must have peerAvailable

,ok 37 peer must have pleaseConnect

,# setup

,2016-02-02 14:21:28.852 ThaliTest[453:685018] jxcore: stopListeningForAdvertisements
,2016-02-02 14:21:28.852 ThaliTest[453:685018] jxcore: stopListeningForAdvertisements: success
,ok 38 Should be able to call stopListeningForAdvertisments in teardown

,2016-02-02 14:21:28.854 ThaliTest[453:685018] jxcore: stopAdvertisingAndListening
,2016-02-02 14:21:28.855 ThaliTest[453:685018] THEMultipeerManager stopping peer
,2016-02-02 14:21:28.856 ThaliTest[453:685018] multipeer manager: stop client timer
,2016-02-02 14:21:28.860 ThaliTest[453:685018] jxcore: stopAdvertisingAndListening: success
,ok 39 Should be able to call stopAdvertisingAndListening in teardown

,# Can connect to a remote peer

,# teardown

,2016-02-02 14:21:30.928 ThaliTest[453:685018] jxcore: startUpdateAdvertisingAndListening
2016-02-02 14:21:30.929 ThaliTest[453:685018] server: starting B0673E8C-23B0-4E2C-B7F0-E2565174D20F:5
,2016-02-02 14:21:30.930 ThaliTest[453:685018] multipeer manager: start client restart timer: 0x15d59350
2016-02-02 14:21:30.930 ThaliTest[453:685018] THEMultipeerManager initialized peer B0673E8C-23B0-4E2C-B7F0-E2565174D20F:5
2016-02-02 14:21:30.930 ThaliTest[453:685018] jxcore: startUpdateAdvertisingAndListening: success
ok 40 Can call startUpdateAdvertisingAndListening without error

,2016-02-02 14:21:30.932 ThaliTest[453:685018] jxcore: startListeningForAdvertisements
2016-02-02 14:21:30.933 ThaliTest[453:685018] multipeer manager: stop client timer
,2016-02-02 14:21:30.935 ThaliTest[453:685018] multipeer manager: start client restart timer: 0x15d59350
2016-02-02 14:21:30.935 ThaliTest[453:685018] jxcore: startListeningForAdvertisements: success
ok 41 Can call startListeningForAdvertisements without error

,2016-02-02 14:21:31.780 ThaliTest[453:684757] client: found new peer: AC42391D-3B67-44B2-83EF-6199949E75E1:4
,2016-02-02 14:21:31.782 ThaliTest[453:685018] jxcore: connect AC42391D-3B67-44B2-83EF-6199949E75E1:4
,2016-02-02 14:21:31.783 ThaliTest[453:685018] client session: connect
,2016-02-02 14:21:31.783 ThaliTest[453:685018] client session: stateChange:0->1 AC42391D-3B67-44B2-83EF-6199949E75E1:4
,2016-02-02 14:21:32.037 ThaliTest[453:684757] multipeer session: reset timer
,2016-02-02 14:21:32.038 ThaliTest[453:684757] server: rejecting invitation from AC42391D-3B67-44B2-83EF-6199949E75E1 due to previous generation (B0673E8C-23B0-4E2C-B7F0-E2565174D20F:5 != B0673E8C-23B0-4E2C-B7F0-E2565174D20F:4)
,2016-02-02 14:21:32.041 ThaliTest[453:685510] client session: not connected AC42391D-3B67-44B2-83EF-6199949E75E1:4
,2016-02-02 14:21:32.041 ThaliTest[453:685510] client session: onLinkFailure: AC42391D-3B67-44B2-83EF-6199949E75E1
,2016-02-02 14:21:32.041 ThaliTest[453:685510] client session: disconnect
,2016-02-02 14:21:32.042 ThaliTest[453:685510] client session: stateChange:1->0 AC42391D-3B67-44B2-83EF-6199949E75E1:4
,2016-02-02 14:21:32.045 ThaliTest[453:685510] client session: fireConnectCallback: AC42391D-3B67-44B2-83EF-6199949E75E1
2016-02-02 14:21:32.045 ThaliTest[453:685510] jxcore: connect: fail: Peer disconnected
,appEnteredForeground wasn't registered

,2016-02-02 14:26:25.985 ThaliTest[453:684757] client: lost peer: AC42391D-3B67-44B2-83EF-6199949E75E1
2016-02-02 14:26:25.985 ThaliTest[453:684757] client session: onPeerLost: AC42391D-3B67-44B2-83EF-6199949E75E1
,2016-02-02 14:26:49.317 ThaliTest[453:684757] client: found updated peer: AC42391D-3B67-44B2-83EF-6199949E75E1:5
,2016-02-02 14:26:49.319 ThaliTest[453:685018] jxcore: connect AC42391D-3B67-44B2-83EF-6199949E75E1:5
,2016-02-02 14:26:49.320 ThaliTest[453:685018] client: connect: unreachable AC42391D-3B67-44B2-83EF-6199949E75E1
2016-02-02 14:26:49.321 ThaliTest[453:685018] jxcore: connect: fail: Peer unreachable
,appEnteringBackground wasn't registered

,appEnteredForeground wasn't registered

,2016-02-02 14:33:52.547 ThaliTest[453:684757] client: lost peer: AC42391D-3B67-44B2-83EF-6199949E75E1
2016-02-02 14:33:52.547 ThaliTest[453:684757] client session: onPeerLost: AC42391D-3B67-44B2-83EF-6199949E75E1
,2016-02-02 14:34:03.684 ThaliTest[453:684757] client: found existing peer: AC42391D-3B67-44B2-83EF-6199949E75E1:5
,2016-02-02 14:34:03.686 ThaliTest[453:685018] jxcore: connect AC42391D-3B67-44B2-83EF-6199949E75E1:5
2016-02-02 14:34:03.686 ThaliTest[453:685018] client: connect: unreachable AC42391D-3B67-44B2-83EF-6199949E75E1
2016-02-02 14:34:03.687 ThaliTest[453:685018] jxcore: connect: fail: Peer unreachable
,appEnteringBackground wasn't registered


```
