#### Test 5753124374916c2_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5753124374916c2/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/F8180E99-7254-4ADC-8DA1-C3026675BBD8/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/F8180E99-7254-4ADC-8DA1-C3026675BBD8/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5753124374916c2/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5753124374916c2/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/3997BD24-6674-4EE3-951C-88252B2436E6/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50683"
,(lldb)     command script import "/tmp/F8180E99-7254-4ADC-8DA1-C3026675BBD8/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-05 15:13:28.160 ThaliTest[719:1122877] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/6F8AB166-0FF5-4D2D-B661-AA278028DB76/Library/Cookies/Cookies.binarycookies
,2016-02-05 15:13:28.541 ThaliTest[719:1122877] Apache Cordova native platform version 3.9.2 is starting.
,2016-02-05 15:13:28.542 ThaliTest[719:1122877] Multi-tasking -> Device: YES, App: YES
,2016-02-05 15:13:28.551 ThaliTest[719:1122877] Unlimited access to network resources
,2016-02-05 15:13:28.560 ThaliTest[719:1122877] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-05 15:13:38.885 ThaliTest[719:1122877] Resetting plugins due to page load.
,2016-02-05 15:13:43.138 ThaliTest[719:1122877] Finished load of: file:///var/mobile/Containers/Bundle/Application/3997BD24-6674-4EE3-951C-88252B2436E6/ThaliTest.app/www/index.html
,2016-02-05 15:13:43.289 ThaliTest[719:1122877] JXcore Cordova plugin initializing
2016-02-05 15:13:43.290 ThaliTest[719:1123148] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

JXcore engine is started
,My device name is: Apple-IpadAir2-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3997BD24-6674-4EE3-951C-88252B2436E6/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3997BD24-6674-4EE3-951C-88252B2436E6/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3997BD24-6674-4EE3-951C-88252B2436E6/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3997BD24-6674-4EE3-951C-88252B2436E6/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/3997BD24-6674-4EE3-951C-88252B2436E6/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded

,TAP version 13

,# setup

,# multiplex can send data

,got: setup_multiplex can send data

ack: setup_multiplex can send data_ok

,# teardown

,ok 1 String should be length:200

,# setup

,# enqueue and run in order

,got: setup_enqueue and run in order

ack: setup_enqueue and run in order_ok

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

,got: setup_basic

,ack: setup_basic_ok

,# teardown

,ok 11 sane

,# setup

,# another

,got: setup_another

,ack: setup_another_ok

,# teardown

,ok 12 sane

,# setup

,# Can call start/stopListeningForAdvertisements

,got: setup_Can call start/stopListeningForAdvertisements

ack: setup_Can call start/stopListeningForAdvertisements_ok

,# teardown

,2016-02-05 15:18:12.126 ThaliTest[719:1123148] jxcore: startListeningForAdvertisements
,2016-02-05 15:18:12.128 ThaliTest[719:1123148] multipeer manager: start client restart timer: 0x14e5dd10
2016-02-05 15:18:12.128 ThaliTest[719:1123148] jxcore: startListeningForAdvertisements: success
,ok 13 Can call startListeningForAdvertisements without error

,2016-02-05 15:18:12.130 ThaliTest[719:1123148] jxcore: stopListeningForAdvertisements
,2016-02-05 15:18:12.131 ThaliTest[719:1123148] multipeer manager: stop client timer
,2016-02-05 15:18:12.131 ThaliTest[719:1123148] jxcore: stopListeningForAdvertisements: success
,ok 14 Can call stopListeningForAdvertisements without error

# setup

discoveryAdvertisingStateUpdate wasn't registered

,discoveryAdvertisingStateUpdate wasn't registered

,2016-02-05 15:18:12.377 ThaliTest[719:1123148] jxcore: stopListeningForAdvertisements
,2016-02-05 15:18:12.377 ThaliTest[719:1123148] jxcore: stopListeningForAdvertisements: success
,ok 15 Should be able to call stopListeningForAdvertisments in teardown

,2016-02-05 15:18:12.379 ThaliTest[719:1123148] jxcore: stopAdvertisingAndListening
,2016-02-05 15:18:12.380 ThaliTest[719:1123148] THEMultipeerManager stopping peer
,2016-02-05 15:18:12.380 ThaliTest[719:1123148] jxcore: stopAdvertisingAndListening: success
,ok 16 Should be able to call stopAdvertisingAndListening in teardown

,# Calling startListeningForAdvertisements twice is an error

,discoveryAdvertisingStateUpdate wasn't registered

,got: setup_Calling startListeningForAdvertisements twice is an error

ack: setup_Calling startListeningForAdvertisements twice is an error_ok

,# teardown

,2016-02-05 15:18:12.580 ThaliTest[719:1123148] jxcore: startListeningForAdvertisements
,2016-02-05 15:18:12.582 ThaliTest[719:1123148] multipeer manager: start client restart timer: 0x14e5dd10
,2016-02-05 15:18:12.582 ThaliTest[719:1123148] jxcore: startListeningForAdvertisements: success
,ok 17 Can call startListeningForAdvertisements without error

2016-02-05 15:18:12.584 ThaliTest[719:1123148] jxcore: startListeningForAdvertisements
2016-02-05 15:18:12.585 ThaliTest[719:1123148] jxcore: startListeningForAdvertisements: failure
ok 18 Calling start twice is an error

,ok 19 Error must be "Call Stop!"

,# setup

,discoveryAdvertisingStateUpdate wasn't registered

,discoveryAdvertisingStateUpdate wasn't registered

,2016-02-05 15:18:12.910 ThaliTest[719:1123148] jxcore: stopListeningForAdvertisements
,2016-02-05 15:18:12.911 ThaliTest[719:1123148] multipeer manager: stop client timer
,2016-02-05 15:18:12.912 ThaliTest[719:1123148] jxcore: stopListeningForAdvertisements: success
,ok 20 Should be able to call stopListeningForAdvertisments in teardown

,2016-02-05 15:18:12.913 ThaliTest[719:1123148] jxcore: stopAdvertisingAndListening
,2016-02-05 15:18:12.914 ThaliTest[719:1123148] THEMultipeerManager stopping peer
2016-02-05 15:18:12.914 ThaliTest[719:1123148] jxcore: stopAdvertisingAndListening: success
,ok 21 Should be able to call stopAdvertisingAndListening in teardown

,# Can call start/stopUpdateAdvertisingAndListening

,discoveryAdvertisingStateUpdate wasn't registered

,got: setup_Can call start/stopUpdateAdvertisingAndListening

ack: setup_Can call start/stopUpdateAdvertisingAndListening_ok

,# teardown

,2016-02-05 15:18:13.050 ThaliTest[719:1123148] jxcore: startUpdateAdvertisingAndListening
,2016-02-05 15:18:13.051 ThaliTest[719:1123148] server: starting 104EA696-8B16-4F69-9896-C2A337571063:1
,2016-02-05 15:18:13.052 ThaliTest[719:1123148] multipeer manager: start client restart timer: 0x14e5dd10
2016-02-05 15:18:13.053 ThaliTest[719:1123148] THEMultipeerManager initialized peer 104EA696-8B16-4F69-9896-C2A337571063:1
2016-02-05 15:18:13.054 ThaliTest[719:1123148] jxcore: startUpdateAdvertisingAndListening: success
,ok 22 Can call startUpdateAdvertisingAndListening without error

,2016-02-05 15:18:13.057 ThaliTest[719:1123148] jxcore: stopAdvertisingAndListening
2016-02-05 15:18:13.057 ThaliTest[719:1123148] THEMultipeerManager stopping peer
2016-02-05 15:18:13.058 ThaliTest[719:1123148] multipeer manager: stop client timer
2016-02-05 15:18:13.058 ThaliTest[719:1123148] jxcore: stopAdvertisingAndListening: success
,ok 23 Can call stopAdvertisingAndListening without error

,# setup

,2016-02-05 15:18:13.504 ThaliTest[719:1123148] jxcore: stopListeningForAdvertisements
,2016-02-05 15:18:13.504 ThaliTest[719:1123148] jxcore: stopListeningForAdvertisements: success
,ok 24 Should be able to call stopListeningForAdvertisments in teardown

,2016-02-05 15:18:13.506 ThaliTest[719:1123148] jxcore: stopAdvertisingAndListening
,2016-02-05 15:18:13.507 ThaliTest[719:1123148] THEMultipeerManager stopping peer
,2016-02-05 15:18:13.507 ThaliTest[719:1123148] jxcore: stopAdvertisingAndListening: success
,ok 25 Should be able to call stopAdvertisingAndListening in teardown

,# Calling startUpdateAdvertisingAndListening twice is NOT and error

,discoveryAdvertisingStateUpdate wasn't registered

,got: setup_Calling startUpdateAdvertisingAndListening twice is NOT and error

ack: setup_Calling startUpdateAdvertisingAndListening twice is NOT and error_ok

,# teardown

,2016-02-05 15:18:14.553 ThaliTest[719:1123148] jxcore: startUpdateAdvertisingAndListening
,2016-02-05 15:18:14.553 ThaliTest[719:1123148] server: starting 104EA696-8B16-4F69-9896-C2A337571063:2
,2016-02-05 15:18:14.555 ThaliTest[719:1123148] multipeer manager: start client restart timer: 0x14e5dd10
2016-02-05 15:18:14.555 ThaliTest[719:1123148] THEMultipeerManager initialized peer 104EA696-8B16-4F69-9896-C2A337571063:2
2016-02-05 15:18:14.556 ThaliTest[719:1123148] jxcore: startUpdateAdvertisingAndListening: success
,ok 26 Can call startUpdateAdvertisingAndListening without error

2016-02-05 15:18:14.559 ThaliTest[719:1123148] jxcore: startUpdateAdvertisingAndListening
2016-02-05 15:18:14.559 ThaliTest[719:1123148] THEMultipeerManager stopping peer
,2016-02-05 15:18:14.560 ThaliTest[719:1123148] multipeer manager: stop client timer
,2016-02-05 15:18:14.560 ThaliTest[719:1123148] server: starting 104EA696-8B16-4F69-9896-C2A337571063:3
,2016-02-05 15:18:14.562 ThaliTest[719:1123148] multipeer manager: start client restart timer: 0x14e5dd10
2016-02-05 15:18:14.562 ThaliTest[719:1123148] THEMultipeerManager initialized peer 104EA696-8B16-4F69-9896-C2A337571063:3
2016-02-05 15:18:14.563 ThaliTest[719:1123148] jxcore: startUpdateAdvertisingAndListening: success
,ok 27 Can call startUpdateAdvertisingAndListening twice without error

,# setup

,2016-02-05 15:18:14.628 ThaliTest[719:1123148] jxcore: stopListeningForAdvertisements
,2016-02-05 15:18:14.629 ThaliTest[719:1123148] jxcore: stopListeningForAdvertisements: success
,ok 28 Should be able to call stopListeningForAdvertisments in teardown

,2016-02-05 15:18:14.631 ThaliTest[719:1123148] jxcore: stopAdvertisingAndListening
,2016-02-05 15:18:14.631 ThaliTest[719:1123148] THEMultipeerManager stopping peer
,2016-02-05 15:18:14.631 ThaliTest[719:1123148] multipeer manager: stop client timer
,2016-02-05 15:18:14.632 ThaliTest[719:1123148] jxcore: stopAdvertisingAndListening: success
,ok 29 Should be able to call stopAdvertisingAndListening in teardown

,# peerAvailabilityChange is called

,discoveryAdvertisingStateUpdate wasn't registered

,got: setup_peerAvailabilityChange is called

ack: setup_peerAvailabilityChange is called_ok

,# teardown

,2016-02-05 15:18:14.981 ThaliTest[719:1123148] jxcore: startUpdateAdvertisingAndListening
,2016-02-05 15:18:14.981 ThaliTest[719:1123148] server: starting 104EA696-8B16-4F69-9896-C2A337571063:4
,2016-02-05 15:18:14.982 ThaliTest[719:1123148] multipeer manager: start client restart timer: 0x14e5dd10
2016-02-05 15:18:14.983 ThaliTest[719:1123148] THEMultipeerManager initialized peer 104EA696-8B16-4F69-9896-C2A337571063:4
2016-02-05 15:18:14.983 ThaliTest[719:1123148] jxcore: startUpdateAdvertisingAndListening: success
,ok 30 Can call startUpdateAdvertisingAndListeningwithout error

,2016-02-05 15:18:14.986 ThaliTest[719:1123148] jxcore: startListeningForAdvertisements
2016-02-05 15:18:14.986 ThaliTest[719:1123148] multipeer manager: stop client timer
2016-02-05 15:18:14.987 ThaliTest[719:1123148] multipeer manager: start client restart timer: 0x14e5dd10
2016-02-05 15:18:14.987 ThaliTest[719:1123148] jxcore: startListeningForAdvertisements: success
,ok 31 Can call startListeningForAdvertisements without error

,discoveryAdvertisingStateUpdate wasn't registered

,2016-02-05 15:18:16.298 ThaliTest[719:1122877] client: found new peer: 500454C9-5940-429C-B7E2-E6139CA81B63:4
,ok 32 peers must be an array

,ok 33 peers must not be zero-length

,ok 34 peer must have peerIdentifier

,ok 35 peerIdentifier must be a string

,ok 36 peer must have peerAvailable

,ok 37 peer must have pleaseConnect

,# setup

,2016-02-05 15:18:17.623 ThaliTest[719:1123148] jxcore: stopListeningForAdvertisements
,2016-02-05 15:18:17.624 ThaliTest[719:1123148] jxcore: stopListeningForAdvertisements: success
,ok 38 Should be able to call stopListeningForAdvertisments in teardown

,2016-02-05 15:18:17.625 ThaliTest[719:1123148] jxcore: stopAdvertisingAndListening
,2016-02-05 15:18:17.626 ThaliTest[719:1123148] THEMultipeerManager stopping peer
,2016-02-05 15:18:17.626 ThaliTest[719:1123148] multipeer manager: stop client timer
2016-02-05 15:18:17.626 ThaliTest[719:1123148] jxcore: stopAdvertisingAndListening: success
ok 39 Should be able to call stopAdvertisingAndListening in teardown

# Can connect to a remote peer

,discoveryAdvertisingStateUpdate wasn't registered

,got: setup_Can connect to a remote peer

ack: setup_Can connect to a remote peer_ok

,# teardown

,2016-02-05 15:18:20.240 ThaliTest[719:1123148] jxcore: startUpdateAdvertisingAndListening
,2016-02-05 15:18:20.241 ThaliTest[719:1123148] server: starting 104EA696-8B16-4F69-9896-C2A337571063:5
,2016-02-05 15:18:20.242 ThaliTest[719:1123148] multipeer manager: start client restart timer: 0x14e5dd10
2016-02-05 15:18:20.243 ThaliTest[719:1123148] THEMultipeerManager initialized peer 104EA696-8B16-4F69-9896-C2A337571063:5
2016-02-05 15:18:20.243 ThaliTest[719:1123148] jxcore: startUpdateAdvertisingAndListening: success
,ok 40 Can call startUpdateAdvertisingAndListening without error

,2016-02-05 15:18:20.245 ThaliTest[719:1123148] jxcore: startListeningForAdvertisements
2016-02-05 15:18:20.246 ThaliTest[719:1123148] multipeer manager: stop client timer
2016-02-05 15:18:20.247 ThaliTest[719:1123148] multipeer manager: start client rest,art timer: 0x14e5dd10
2016-02-05 15:18:20.247 ThaliTest[719:1123148] jxcore: startListeningForAdvertisements: success
ok 41 Can call startListeningForAdvertisements without error

discoveryAdvertisingStateUpdate wasn't registered

,2016-02-05 15:18:21.120 ThaliTest[719:1122877] client: found new peer: 500454C9-5940-429C-B7E2-E6139CA81B63:4
,2016-02-05 15:18:21.122 ThaliTest[719:1123148] jxcore: connect 500454C9-5940-429C-B7E2-E6139CA81B63:4
2016-02-05 15:18:21.123 ThaliTest[719:1123148] client: server will connect
2016-02-05 15:18:21.123 ThaliTest[719:1123148] client session: reverseConnect,
2016-02-05 15:18:21.124 ThaliTest[719:1123148] client session: stateChange:0->1 500454C9-5940-429C-B7E2-E6139CA81B63:4
,2016-02-05 15:18:21.707 ThaliTest[719:1123633] client session: not connected 500454C9-5940-429C-B7E2-E6139CA81B63:4
2016-02-05 15:18:21.707 ThaliTest[719:1123633] client session: onLinkFailure: 500454C9-5940-429C-B7E2-E6139CA81B63
,2016-02-05 15:18:21.707 ThaliTest[719:1123633] client session: disconnect
2016-02-05 15:18:21.708 ThaliTest[719:1123633] client session: stateChange:1->0 500454C9-5940-429C-B7E2-E6139CA81B63:4
,2016-02-05 15:18:21.708 ThaliTest[719:1123633] client session: no connect callback (server initiated)
,2016-02-05 15:18:22.656 ThaliTest[719:1122877] multipeer session: reset timer
,2016-02-05 15:18:22.657 ThaliTest[719:1122877] server session: connect
,2016-02-05 15:18:22.657 ThaliTest[719:1122877] server session: stateChange:0->1 500454C9-5940-429C-B7E2-E6139CA81B63:5
,2016-02-05 15:18:22.664 ThaliTest[719:1122877] server: accepting invitation 500454C9-5940-429C-B7E2-E6139CA81B63
,2016-02-05 15:18:25.485 ThaliTest[719:1123633] server session: connected
2016-02-05 15:18:25.485 ThaliTest[719:1123633] server session: stateChange:1->2 500454C9-5940-429C-B7E2-E6139CA81B63:5
,2016-02-05 15:18:25.525 ThaliTest[719:1122877] server relay: connected (to port: 4242)
,2016-02-05 15:18:25.527 ThaliTest[719:1122877] jxcore: connect: success
,{ clientPort: 53656, serverPort: 4242, listeningPort: 0 }

,not ok 42 Connection must have listeningPort

  ---

,    operator: ok

,    expected: true

    actual:   0

,  ...

,ok 43 listeningPort must be a number

,ok 44 Connection must have clientPort

,not ok 45 clientPort must be null

  ---

,    operator: ok
,
,    expected: true

,    actual:   false

,  ...

,ok 46 Connection must have serverPort

,not ok 47 serverPort must be null

  ---
,
,    operator: ok

,    expected: true

,    actual:   false

,  ...

,# setup

,2016-02-05 15:18:27.000 ThaliTest[719:1123148] jxcore: stopListeningForAdvertisements
,2016-02-05 15:18:27.000 ThaliTest[719:1123148] jxcore: stopListeningForAdvertisements: success
,ok 48 Should be able to call stopListeningForAdvertisments in teardown

,2016-02-05 15:18:27.002 ThaliTest[719:1123148] jxcore: stopAdvertisingAndListening
2016-02-05 15:18:27.003 ThaliTest[719:1123148] THEMultipeerManager stopping peer
2016-02-05 15:18:27.003 ThaliTest[719:1123148] server session: disconnect
,2016-02-05 15:18:27.003 ThaliTest[719:1123148] server session: stateChange:2->0 500454C9-5940-429C-B7E2-E6139CA81B63:5
,2016-02-05 15:18:27.024 ThaliTest[719:1123148] multipeer manager: stop client timer
2016-02-05 15:18:27.024 ThaliTest[719:1123148] jxcore: stopAdvertisingAndListening: success
ok 49 Should be able to call stopAdvertisingAndListening in teardown

# Afte,r #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

,discoveryAdvertisingStateUpdate wasn't registered

,got: setup_After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

,ack: setup_After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted_ok

,# teardown

,ok 50 host address should match

,ok 51 port should match

,ok 52 peer should be available

,ok 53 peer should be unavailable

,# setup

,# #startUpdateAdvertisingAndListening should use different USN after every invocation

,got: setup_#startUpdateAdvertisingAndListening should use different USN after every invocation

,ack: setup_#startUpdateAdvertisingAndListening should use different USN after every invocation_ok

,# teardown

,ok 54 when receiving the first byebye, the second USN should not be set yet

,ok 55 USN should have changed from the first one

,ok 56 when receiving the second byebye, the first USN should be already set

,# setup

,# messages with invalid location or USN should be ignored

,got: setup_messages with invalid location or USN should be ignored

,ack: setup_messages with invalid location or USN should be ignored_ok

,# teardown

,WARN thaliWifiInfrastructure Failed to parse a valid port number from location: http://foo.bar:90000

,ok 57 should not have emitted with invalid port

,WARN thaliWifiInfrastructure Received an invalid USN value: 

,ok 58 should not have emitted with invalid USN

,# setup

,# verify that Thali-specific messages are filtered correctly

,got: setup_verify that Thali-specific messages are filtered correctly

,ack: setup_verify that Thali-specific messages are filtered correctly_ok

,# teardown

,ok 59 irrelevant messages should be ignored

,ok 60 relevant messages should not be ignored

,ok 61 messages from this device should be ignored

,# setup

,# #start should fail if called twice in a row

,got: setup_#start should fail if called twice in a row

ack: setup_#start should fail if called twice in a row_ok

,# teardown

,ok 62 specific error should be received

,# setup

,# #startUpdateAdvertisingAndListening should fail invalid router has been passed

,got: setup_#startUpdateAdvertisingAndListening should fail invalid router has been passed

,ack: setup_#startUpdateAdvertisingAndListening should fail invalid router has been passed_ok

,# teardown

,ERROR thaliWifiInfrastructure Unable to use the given router: TypeError: Router.use() requires middleware function but got a string

,ok 63 specific error should be received

,# setup

,# #startUpdateAdvertisingAndListening should fail if router server starting fails

,got: setup_#startUpdateAdvertisingAndListening should fail if router server starting fails

,ack: setup_#startUpdateAdvertisingAndListening should fail if router server starting fails_ok

,# teardown

,ERROR thaliWifiInfrastructure Router server emitted an error: Error: listen EADDRINUSE

,ok 64 specific error expected

,# setup

,# #startUpdateAdvertisingAndListening should start hosting given router object

,got: setup_#startUpdateAdvertisingAndListening should start hosting given router object

,ack: setup_#startUpdateAdvertisingAndListening should start hosting given router object_ok

,# teardown

,ok 65 server should respond with code 200

,# setup

,# #stop can be called multiple times in a row

,got: setup_#stop can be called multiple times in a row

ack: setup_#stop can be called multiple times in a row_ok

,# teardown

,ok 66 should be in stopped state

,ok 67 should still be in stopped state

,# setup

,# #startListeningForAdvertisements can be called multiple times in a row

,got: setup_#startListeningForAdvertisements can be called multiple times in a row

,ack: setup_#startListeningForAdvertisements can be called multiple times in a row_ok

,# teardown

,ok 68 should be in listening state

,ok 69 should still be in listening state

,# setup

,# #stopListeningForAdvertisements can be called multiple times in a row

,got: setup_#stopListeningForAdvertisements can be called multiple times in a row

ack: setup_#stopListeningForAdvertisements can be called multiple times in a row_ok

,# teardown

,ok 70 should not be in listening state

,ok 71 should still not be in listening state

,# setup

,# #stopAdvertisingAndListening can be called multiple times in a row

,got: setup_#stopAdvertisingAndListening can be called multiple times in a row

ack: setup_#stopAdvertisingAndListening can be called multiple times in a row_ok

,# teardown

,ok 72 should not be in advertising state

,ok 73 should still not be in advertising state

,# setup

,# functions are run from a queue in the right order

,got: setup_functions are run from a queue in the right order

ack: setup_functions are run from a queue in the right order_ok

,# teardown

,ok 74 call order must match

,Tests Complete

,Total: 0	Passed: 0	Failed: 0

,****TEST TOOK:  ms ****

****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****


```
